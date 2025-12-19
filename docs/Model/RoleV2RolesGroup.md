# # RoleV2RolesGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**applications** | [**array<string,\TalonOne\Client\Model\RoleV2ApplicationDetails>**](RoleV2ApplicationDetails.md) | A map of the link between the Application, campaign, or draft campaign-related permission set and the Application ID the permissions apply to. | [optional]
**loyaltyPrograms** | **array<string,string>** | A map of the link between the loyalty program-related permission set and the Application ID the permissions apply to. | [optional]
**campaignAccessGroups** | **array<string,string>** | A map of the link between the campaign access group-related permission set and the Application ID the permissions apply to. | [optional]
**account** | **string** | Name of the account-level permission set | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
