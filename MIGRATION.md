# Migration guide

This document provides guidance on how to migrate from the [legacy version](https://github.com/talon-one/TalonOnePHPsdk)
of the SDK to the latest version. Follow the steps below to ensure a smooth transition.

## PHP version requirement

The new SDK requires **PHP 8.1 or later**. Ensure your environment meets this requirement.
The legacy SDK supported PHP 7.1+.

## Update composer.json

In your `composer.json` file, replace the legacy SDK package with the new one.

**Before**

```json
{
  "require": {
    "talon-one/talon-one-client": "^25.16"
  }
}
```

**After**

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "<https://github.com/talon-one/talon-one-php-sdk.git>"
    }
  ],
  "require": {
    "talon-one/talon-one-php-sdk": "dev-main"
  }
}
```

After updating the file, run `composer update` to install the new version.

## Code changes

### Namespace

The namespace `TalonOne\Client` remains the same. You do not need to update your `use`
statements for API clients or models.

### Client initialization

The client initialization code is mostly unchanged. You can still use
`\TalonOne\Client\Configuration::getDefaultConfiguration()` to configure the client and
instantiate the API clients (`\TalonOne\Client\Api\IntegrationApi` and
`\TalonOne\Client\Api\ManagementApi()`).

### API method signatures

Across both `IntegrationApi` and `ManagementApi`, the method signatures for API calls have
been updated with more specific parameter names and native PHP type hints. You will need
to update your code to match the new signatures. This applies to all methods that accept a
body payload. The generic `$body` parameter has been replaced with a more descriptive name
based on the model being sent.

This change is breaking if you are using named parameters. Update your code and replace
parameter names accordingly. If you are not using named parameters, no changes are
required.

The new methods also include an optional `$contentType` parameter, which you can generally
ignore unless you have specific needs.

**Example 1: `IntegrationApi`**

A common example is the `updateCustomerSessionV2` method.

**Before**

```php
$integrationApi->updateCustomerSessionV2($customer_session_id, $body);
```

**After**

The parameter for the request body is now named `$integration_request`.

```php
$integrationApi->updateCustomerSessionV2($customer_session_id, $integration_request);
```

**Example 2: `ManagementApi`**

The same applies to the `updateCampaign` method in the `ManagementApi`.

**Before**

```php
$managementApi->updateCampaign($applicationId, $campaignId, $body);
```

**After**

The parameter for the request body is now named `$update_campaign`.

```php
$managementApi->updateCampaign($applicationId, $campaignId, $update_campaign);
```

### Models

The model classes and their properties remain mostly unchanged. However, we recommend
testing your code thoroughly after migration to ensure that all data is being correctly
serialized and deserialized.

## Payload changes

While most request and response payloads remain backward-compatible, there are some
important changes and additions to be aware of.

### `returnCartItems` (Breaking Change)

- **Request:** The `ReturnIntegrationRequest` payload is backward-compatible.
- **Response:** This method's response has a **breaking change**.
  - The legacy SDK returned an `IntegrationState` object.
  - The new SDK returns an `IntegrationStateV2` object.

The `IntegrationStateV2` object is much more comprehensive. You **must** update any code
that processes the response of the `returnCartItems` method to handle the new
`IntegrationStateV2` structure.

In general, while most other payloads have not changed, it is critical to **test all API
interactions** after migrating to ensure your application handles all request and response
data correctly.

## Summary of changes

| Category             | Legacy SDK                              | New SDK                                     | Action Required                                                                                                                             |
| -------------------- | --------------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **PHP Version**      | 7.1+                                    | 8.1+                                        | Upgrade your PHP environment.                                                                                                               |
| **Composer Package** | `talon-one/talon-one-client`            | `talon-one/talon-one-php-sdk`               | Update your `composer.json` file.                                                                                                           |
| **Namespace**        | `TalonOne\Client`                       | `TalonOne\Client`                           | None.                                                                                                                                       |
| **API Methods**      | Docblock types, generic parameter names | Native type hints, specific parameter names | Update parameter names in method calls to match the new, more descriptive names. Review all passed parameters to ensure type compatibility. |
| **Models**           | Generally stable                        | Generally stable, some breaking changes     | Review payload changes. Test all integrations.                                                                                              |
