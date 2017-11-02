---
title: "msdyn_requirementresourcepreference Entity Reference (Developer Guide for Dynamics 365 Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_requirementresourcepreference entity."
ms.date: 10/31/2017
ms.service: "crm-online"
ms.topic: "reference"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "JimDaly"
ms.author: "jdaly"
manager: "jdaly"
---
# msdyn_requirementresourcepreference Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]

Requirement Resource Preference

**Added by**: Unified Resource Scheduling Solution<br />

## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Assign|PATCH [*org URI*]/api/data/v9.0/msdyn_requirementresourcepreferences(*msdyn_requirementresourcepreferenceid*)<br />[Update](../webapi/update-delete-entities-using-web-api.md#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|Create|POST [*org URI*]/api/data/v9.0/msdyn_requirementresourcepreferences<br />See [Create](../webapi/create-entity-web-api.md)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/msdyn_requirementresourcepreferences(*msdyn_requirementresourcepreferenceid*)<br />See [Delete](../webapi/update-delete-entities-using-web-api.md#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref href="Microsoft.Dynamics.CRM.GrantAccess?text=GrantAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|IsValidStateTransition|<xref href="Microsoft.Dynamics.CRM.IsValidStateTransition?text=IsValidStateTransition Function" />|<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
|ModifyAccess|<xref href="Microsoft.Dynamics.CRM.ModifyAccess?text=ModifyAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|Retrieve|GET [*org URI*]/api/data/v9.0/msdyn_requirementresourcepreferences(*msdyn_requirementresourcepreferenceid*)<br />See [Retrieve](../webapi/retrieve-entity-using-web-api.md)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_requirementresourcepreferences<br />See [Query Data](../webapi/query-data-web-api.md)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref href="Microsoft.Dynamics.CRM.RetrievePrincipalAccess?text=RetrievePrincipalAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref href="Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?text=RetrieveSharedPrincipalsAndAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref href="Microsoft.Dynamics.CRM.RevokeAccess?text=RevokeAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|SetState|PATCH [*org URI*]/api/data/v9.0/msdyn_requirementresourcepreferences(*msdyn_requirementresourcepreferenceid*)<br />[Update](../webapi/update-delete-entities-using-web-api.md#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|PATCH [*org URI*]/api/data/v9.0/msdyn_requirementresourcepreferences(*msdyn_requirementresourcepreferenceid*)<br />See [Update](../webapi/update-delete-entities-using-web-api.md#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Properties

**DisplayName**: Requirement Resource Preference<br />
**DisplayCollectionName**: Requirement Resource Preferences<br />
**SchemaName**: msdyn_requirementresourcepreference<br />
**CollectionSchemaName**: msdyn_requirementresourcepreferences<br />
**LogicalName**: msdyn_requirementresourcepreference<br />
**LogicalCollectionName**: msdyn_requirementresourcepreferences<br />
**EntitySetName**: msdyn_requirementresourcepreferences<br />
**PrimaryIdAttribute**: msdyn_requirementresourcepreferenceid<br />
**PrimaryNameAttribute**: msdyn_name<br />
**OwnershipType**: UserOwned<br />
**IsBPFEntity**: False<br />
<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_Account](#BKMK_msdyn_Account)
- [msdyn_BookableResource](#BKMK_msdyn_BookableResource)
- [msdyn_Cascade](#BKMK_msdyn_Cascade)
- [msdyn_ExpirationDate](#BKMK_msdyn_ExpirationDate)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_PreferenceType](#BKMK_msdyn_PreferenceType)
- [msdyn_requirementresourcepreferenceId](#BKMK_msdyn_requirementresourcepreferenceId)
- [msdyn_ResourceRequirement](#BKMK_msdyn_ResourceRequirement)
- [msdyn_WorkOrder](#BKMK_msdyn_WorkOrder)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

**Description**: Sequence number of the import that created this record.<br />
**DisplayName**: Import Sequence Number<br />
**LogicalName**: importsequencenumber<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**IsValidForUpdate**: False<br />
**Type**: Integer<br />
**Format**: None<br />
**MaxValue**: 2147483647<br />
**MinValue**: -2147483648


### <a name="BKMK_msdyn_Account"></a> msdyn_Account

**Added by**: Field Service Solution<br />
**Description**: <br />
**DisplayName**: Account<br />
**LogicalName**: msdyn_account<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: account


### <a name="BKMK_msdyn_BookableResource"></a> msdyn_BookableResource

**Description**: Bookable Resource<br />
**DisplayName**: Bookable Resource<br />
**LogicalName**: msdyn_bookableresource<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: ApplicationRequired<br />
**Type**: Lookup<br />
**Targets**: bookableresource


### <a name="BKMK_msdyn_Cascade"></a> msdyn_Cascade

**Added by**: Field Service Solution<br />
**Description**: <br />
**DisplayName**: Cascade<br />
**LogicalName**: msdyn_cascade<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Boolean<br />
**Options**:

- **TrueOption Value**: 1 **Label**: Yes
- **FalseOption Value**: 0 **Label**: No

**DefaultValue**: False


### <a name="BKMK_msdyn_ExpirationDate"></a> msdyn_ExpirationDate

**Description**: The date and time when a restricted resource is no longer restricted.<br />
**DisplayName**: Expiration Date<br />
**LogicalName**: msdyn_expirationdate<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: DateTime<br />
**DateTimeBehavior**: UserLocal<br />
**Format**: DateAndTime


### <a name="BKMK_msdyn_name"></a> msdyn_name

**Description**: The name of the custom entity.<br />
**DisplayName**: Name<br />
**LogicalName**: msdyn_name<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: ApplicationRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_PreferenceType"></a> msdyn_PreferenceType

**Description**: Preference Type<br />
**DisplayName**: Preference Type<br />
**LogicalName**: msdyn_preferencetype<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: ApplicationRequired<br />
**Type**: Picklist<br />
**Options**:

- **Value**: 690970000 **Label**: Preferred
- **Value**: 690970001 **Label**: Restricted



### <a name="BKMK_msdyn_requirementresourcepreferenceId"></a> msdyn_requirementresourcepreferenceId

**Description**: The unique identifier for an entity instance.<br />
**DisplayName**: Requirement Resource Preference<br />
**LogicalName**: msdyn_requirementresourcepreferenceid<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**IsValidForUpdate**: False<br />
**Type**: Uniqueidentifier<br />


### <a name="BKMK_msdyn_ResourceRequirement"></a> msdyn_ResourceRequirement

**Description**: Resource Requirement<br />
**DisplayName**: Resource Requirement<br />
**LogicalName**: msdyn_resourcerequirement<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: msdyn_resourcerequirement


### <a name="BKMK_msdyn_WorkOrder"></a> msdyn_WorkOrder

**Added by**: Field Service Solution<br />
**Description**: Unique identifier for Work Order associated with Requirement Resource Preference.<br />
**DisplayName**: Work Order<br />
**LogicalName**: msdyn_workorder<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: msdyn_workorder


### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

**Description**: Date and time that the record was migrated.<br />
**DisplayName**: Record Created On<br />
**LogicalName**: overriddencreatedon<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**IsValidForUpdate**: False<br />
**Type**: DateTime<br />
**DateTimeBehavior**: UserLocal<br />
**Format**: DateOnly


### <a name="BKMK_OwnerId"></a> OwnerId

**Description**: Owner Id<br />
**DisplayName**: Owner<br />
**LogicalName**: ownerid<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: Owner<br />
**Targets**: systemuser,team


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

**Description**: Owner Id Type<br />
**DisplayName**: <br />
**LogicalName**: owneridtype<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: EntityName<br />


### <a name="BKMK_statecode"></a> statecode

**Description**: Status of the Requirement Resource Preference<br />
**DisplayName**: Status<br />
**LogicalName**: statecode<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**IsValidForCreate**: False<br />
**Type**: State<br />
**Options**:

- **Value**: 0 **Label**: Active **DefaultStatus**: 1 **InvariantName**: Active
- **Value**: 1 **Label**: Inactive **DefaultStatus**: 2 **InvariantName**: Inactive



### <a name="BKMK_statuscode"></a> statuscode

**Description**: Reason for the status of the Requirement Resource Preference<br />
**DisplayName**: Status Reason<br />
**LogicalName**: statuscode<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Status<br />
**Options**:

- **Value**: 1 **Label**: Active **State**: 0
- **Value**: 2 **Label**: Inactive **State**: 1



### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

**Description**: For internal use only.<br />
**DisplayName**: Time Zone Rule Version Number<br />
**LogicalName**: timezoneruleversionnumber<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Integer<br />
**Format**: None<br />
**MaxValue**: 2147483647<br />
**MinValue**: -1


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

**Description**: Time zone code that was in use when the record was created.<br />
**DisplayName**: UTC Conversion Time Zone Code<br />
**LogicalName**: utcconversiontimezonecode<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Integer<br />
**Format**: None<br />
**MaxValue**: 2147483647<br />
**MinValue**: -1

<a name="read-only-attributes"></a>
## Read-only attributes
These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [msdyn_AccountName](#BKMK_msdyn_AccountName)
- [msdyn_AccountYomiName](#BKMK_msdyn_AccountYomiName)
- [msdyn_BookableResourceName](#BKMK_msdyn_BookableResourceName)
- [msdyn_ResourceRequirementName](#BKMK_msdyn_ResourceRequirementName)
- [msdyn_WorkOrderName](#BKMK_msdyn_WorkOrderName)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_CreatedBy"></a> CreatedBy

**Description**: Unique identifier of the user who created the record.<br />
**DisplayName**: Created By<br />
**LogicalName**: createdby<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_CreatedByName"></a> CreatedByName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: createdbyname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: createdbyyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_CreatedOn"></a> CreatedOn

**Description**: Date and time when the record was created.<br />
**DisplayName**: Created On<br />
**LogicalName**: createdon<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: DateTime<br />
**DateTimeBehavior**: UserLocal<br />
**Format**: DateAndTime


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

**Description**: Unique identifier of the delegate user who created the record.<br />
**DisplayName**: Created By (Delegate)<br />
**LogicalName**: createdonbehalfby<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: createdonbehalfbyname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: createdonbehalfbyyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_ModifiedBy"></a> ModifiedBy

**Description**: Unique identifier of the user who modified the record.<br />
**DisplayName**: Modified By<br />
**LogicalName**: modifiedby<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: modifiedbyname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: modifiedbyyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

**Description**: Date and time when the record was modified.<br />
**DisplayName**: Modified On<br />
**LogicalName**: modifiedon<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: DateTime<br />
**DateTimeBehavior**: UserLocal<br />
**Format**: DateAndTime


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

**Description**: Unique identifier of the delegate user who modified the record.<br />
**DisplayName**: Modified By (Delegate)<br />
**LogicalName**: modifiedonbehalfby<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: modifiedonbehalfbyname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: modifiedonbehalfbyyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_AccountName"></a> msdyn_AccountName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_accountname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 160


### <a name="BKMK_msdyn_AccountYomiName"></a> msdyn_AccountYomiName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_accountyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 160


### <a name="BKMK_msdyn_BookableResourceName"></a> msdyn_BookableResourceName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_bookableresourcename<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_ResourceRequirementName"></a> msdyn_ResourceRequirementName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_resourcerequirementname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_WorkOrderName"></a> msdyn_WorkOrderName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_workordername<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

**Description**: Name of the owner<br />
**DisplayName**: <br />
**LogicalName**: owneridname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

**Description**: Yomi name of the owner<br />
**DisplayName**: <br />
**LogicalName**: owneridyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

**Description**: Unique identifier for the business unit that owns the record<br />
**DisplayName**: Owning Business Unit<br />
**LogicalName**: owningbusinessunit<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: businessunit


### <a name="BKMK_OwningTeam"></a> OwningTeam

**Description**: Unique identifier for the team that owns the record.<br />
**DisplayName**: Owning Team<br />
**LogicalName**: owningteam<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: team


### <a name="BKMK_OwningUser"></a> OwningUser

**Description**: Unique identifier for the user that owns the record.<br />
**DisplayName**: Owning User<br />
**LogicalName**: owninguser<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_VersionNumber"></a> VersionNumber

**Description**: Version Number<br />
**DisplayName**: Version Number<br />
**LogicalName**: versionnumber<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: BigInt<br />
**MaxValue**: 9223372036854775807<br />
**MinValue**: -9223372036854775808<br />

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [msdyn_requirementresourcepreference_SyncErrors](#BKMK_msdyn_requirementresourcepreference_SyncErrors)
- [msdyn_requirementresourcepreference_DuplicateMatchingRecord](#BKMK_msdyn_requirementresourcepreference_DuplicateMatchingRecord)
- [msdyn_requirementresourcepreference_DuplicateBaseRecord](#BKMK_msdyn_requirementresourcepreference_DuplicateBaseRecord)
- [msdyn_requirementresourcepreference_AsyncOperations](#BKMK_msdyn_requirementresourcepreference_AsyncOperations)
- [msdyn_requirementresourcepreference_MailboxTrackingFolders](#BKMK_msdyn_requirementresourcepreference_MailboxTrackingFolders)
- [msdyn_requirementresourcepreference_UserEntityInstanceDatas](#BKMK_msdyn_requirementresourcepreference_UserEntityInstanceDatas)
- [msdyn_requirementresourcepreference_ProcessSession](#BKMK_msdyn_requirementresourcepreference_ProcessSession)
- [msdyn_requirementresourcepreference_BulkDeleteFailures](#BKMK_msdyn_requirementresourcepreference_BulkDeleteFailures)
- [msdyn_requirementresourcepreference_PrincipalObjectAttributeAccesses](#BKMK_msdyn_requirementresourcepreference_PrincipalObjectAttributeAccesses)
- [msdyn_requirementresourcepreference_Annotations](#BKMK_msdyn_requirementresourcepreference_Annotations)


### <a name="BKMK_msdyn_requirementresourcepreference_SyncErrors"></a> msdyn_requirementresourcepreference_SyncErrors

Same as syncerror entity [msdyn_requirementresourcepreference_SyncErrors](syncerror.md#BKMK_msdyn_requirementresourcepreference_SyncErrors) Many-To-One relationship.

**ReferencingEntity**: syncerror<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_SyncErrors<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: Cascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: Cascade
- **Share**: Cascade
- **Unshare**: Cascade


### <a name="BKMK_msdyn_requirementresourcepreference_DuplicateMatchingRecord"></a> msdyn_requirementresourcepreference_DuplicateMatchingRecord

Same as duplicaterecord entity [msdyn_requirementresourcepreference_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_requirementresourcepreference_DuplicateMatchingRecord) Many-To-One relationship.

**ReferencingEntity**: duplicaterecord<br />
**ReferencingAttribute**: duplicaterecordid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_DuplicateMatchingRecord<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_requirementresourcepreference_DuplicateBaseRecord"></a> msdyn_requirementresourcepreference_DuplicateBaseRecord

Same as duplicaterecord entity [msdyn_requirementresourcepreference_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_requirementresourcepreference_DuplicateBaseRecord) Many-To-One relationship.

**ReferencingEntity**: duplicaterecord<br />
**ReferencingAttribute**: baserecordid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_DuplicateBaseRecord<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_requirementresourcepreference_AsyncOperations"></a> msdyn_requirementresourcepreference_AsyncOperations

Same as asyncoperation entity [msdyn_requirementresourcepreference_AsyncOperations](asyncoperation.md#BKMK_msdyn_requirementresourcepreference_AsyncOperations) Many-To-One relationship.

**ReferencingEntity**: asyncoperation<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_AsyncOperations<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: NoCascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_requirementresourcepreference_MailboxTrackingFolders"></a> msdyn_requirementresourcepreference_MailboxTrackingFolders

Same as mailboxtrackingfolder entity [msdyn_requirementresourcepreference_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_requirementresourcepreference_MailboxTrackingFolders) Many-To-One relationship.

**ReferencingEntity**: mailboxtrackingfolder<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_MailboxTrackingFolders<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: Cascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: Cascade
- **Share**: Cascade
- **Unshare**: Cascade


### <a name="BKMK_msdyn_requirementresourcepreference_UserEntityInstanceDatas"></a> msdyn_requirementresourcepreference_UserEntityInstanceDatas

Same as userentityinstancedata entity [msdyn_requirementresourcepreference_UserEntityInstanceDatas](userentityinstancedata.md#BKMK_msdyn_requirementresourcepreference_UserEntityInstanceDatas) Many-To-One relationship.

**ReferencingEntity**: userentityinstancedata<br />
**ReferencingAttribute**: objectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_UserEntityInstanceDatas<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_requirementresourcepreference_ProcessSession"></a> msdyn_requirementresourcepreference_ProcessSession

Same as processsession entity [msdyn_requirementresourcepreference_ProcessSession](processsession.md#BKMK_msdyn_requirementresourcepreference_ProcessSession) Many-To-One relationship.

**ReferencingEntity**: processsession<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_ProcessSession<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: NoCascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_requirementresourcepreference_BulkDeleteFailures"></a> msdyn_requirementresourcepreference_BulkDeleteFailures

Same as bulkdeletefailure entity [msdyn_requirementresourcepreference_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_requirementresourcepreference_BulkDeleteFailures) Many-To-One relationship.

**ReferencingEntity**: bulkdeletefailure<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_BulkDeleteFailures<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_requirementresourcepreference_PrincipalObjectAttributeAccesses"></a> msdyn_requirementresourcepreference_PrincipalObjectAttributeAccesses

Same as principalobjectattributeaccess entity [msdyn_requirementresourcepreference_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_requirementresourcepreference_PrincipalObjectAttributeAccesses) Many-To-One relationship.

**ReferencingEntity**: principalobjectattributeaccess<br />
**ReferencingAttribute**: objectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_PrincipalObjectAttributeAccesses<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_requirementresourcepreference_Annotations"></a> msdyn_requirementresourcepreference_Annotations

Same as annotation entity [msdyn_requirementresourcepreference_Annotations](annotation.md#BKMK_msdyn_requirementresourcepreference_Annotations) Many-To-One relationship.

**ReferencingEntity**: annotation<br />
**ReferencingAttribute**: objectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_requirementresourcepreference_Annotations<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: Cascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: Cascade
- **Share**: Cascade
- **Unshare**: Cascade

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [lk_msdyn_requirementresourcepreference_createdby](#BKMK_lk_msdyn_requirementresourcepreference_createdby)
- [lk_msdyn_requirementresourcepreference_createdonbehalfby](#BKMK_lk_msdyn_requirementresourcepreference_createdonbehalfby)
- [lk_msdyn_requirementresourcepreference_modifiedby](#BKMK_lk_msdyn_requirementresourcepreference_modifiedby)
- [lk_msdyn_requirementresourcepreference_modifiedonbehalfby](#BKMK_lk_msdyn_requirementresourcepreference_modifiedonbehalfby)
- [user_msdyn_requirementresourcepreference](#BKMK_user_msdyn_requirementresourcepreference)
- [team_msdyn_requirementresourcepreference](#BKMK_team_msdyn_requirementresourcepreference)
- [business_unit_msdyn_requirementresourcepreference](#BKMK_business_unit_msdyn_requirementresourcepreference)
- [msdyn_bookableresource_msdyn_requirementresourcepreference_BookableResource](#BKMK_msdyn_bookableresource_msdyn_requirementresourcepreference_BookableResource)
- [msdyn_resourcerequirement_requirementresourcepreference_ResourceRequirement](#BKMK_msdyn_resourcerequirement_requirementresourcepreference_ResourceRequirement)
- [msdyn_account_msdyn_requirementresourcepreference_Account](#BKMK_msdyn_account_msdyn_requirementresourcepreference_Account)
- [msdyn_msdyn_workorder_msdyn_requirementresourcepreference_WorkOrder](#BKMK_msdyn_msdyn_workorder_msdyn_requirementresourcepreference_WorkOrder)


### <a name="BKMK_lk_msdyn_requirementresourcepreference_createdby"></a> lk_msdyn_requirementresourcepreference_createdby

See systemuser Entity [lk_msdyn_requirementresourcepreference_createdby](systemuser.md#BKMK_lk_msdyn_requirementresourcepreference_createdby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_requirementresourcepreference_createdonbehalfby"></a> lk_msdyn_requirementresourcepreference_createdonbehalfby

See systemuser Entity [lk_msdyn_requirementresourcepreference_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_requirementresourcepreference_createdonbehalfby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_requirementresourcepreference_modifiedby"></a> lk_msdyn_requirementresourcepreference_modifiedby

See systemuser Entity [lk_msdyn_requirementresourcepreference_modifiedby](systemuser.md#BKMK_lk_msdyn_requirementresourcepreference_modifiedby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_requirementresourcepreference_modifiedonbehalfby"></a> lk_msdyn_requirementresourcepreference_modifiedonbehalfby

See systemuser Entity [lk_msdyn_requirementresourcepreference_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_requirementresourcepreference_modifiedonbehalfby) One-To-Many relationship.

### <a name="BKMK_user_msdyn_requirementresourcepreference"></a> user_msdyn_requirementresourcepreference

See systemuser Entity [user_msdyn_requirementresourcepreference](systemuser.md#BKMK_user_msdyn_requirementresourcepreference) One-To-Many relationship.

### <a name="BKMK_team_msdyn_requirementresourcepreference"></a> team_msdyn_requirementresourcepreference

See team Entity [team_msdyn_requirementresourcepreference](team.md#BKMK_team_msdyn_requirementresourcepreference) One-To-Many relationship.

### <a name="BKMK_business_unit_msdyn_requirementresourcepreference"></a> business_unit_msdyn_requirementresourcepreference

See businessunit Entity [business_unit_msdyn_requirementresourcepreference](businessunit.md#BKMK_business_unit_msdyn_requirementresourcepreference) One-To-Many relationship.

### <a name="BKMK_msdyn_bookableresource_msdyn_requirementresourcepreference_BookableResource"></a> msdyn_bookableresource_msdyn_requirementresourcepreference_BookableResource

See bookableresource Entity [msdyn_bookableresource_msdyn_requirementresourcepreference_BookableResource](bookableresource.md#BKMK_msdyn_bookableresource_msdyn_requirementresourcepreference_BookableResource) One-To-Many relationship.

### <a name="BKMK_msdyn_resourcerequirement_requirementresourcepreference_ResourceRequirement"></a> msdyn_resourcerequirement_requirementresourcepreference_ResourceRequirement

See msdyn_resourcerequirement Entity [msdyn_resourcerequirement_requirementresourcepreference_ResourceRequirement](msdyn_resourcerequirement.md#BKMK_msdyn_resourcerequirement_requirementresourcepreference_ResourceRequirement) One-To-Many relationship.

### <a name="BKMK_msdyn_account_msdyn_requirementresourcepreference_Account"></a> msdyn_account_msdyn_requirementresourcepreference_Account

See account Entity [msdyn_account_msdyn_requirementresourcepreference_Account](account.md#BKMK_msdyn_account_msdyn_requirementresourcepreference_Account) One-To-Many relationship.

### <a name="BKMK_msdyn_msdyn_workorder_msdyn_requirementresourcepreference_WorkOrder"></a> msdyn_msdyn_workorder_msdyn_requirementresourcepreference_WorkOrder

See msdyn_workorder Entity [msdyn_msdyn_workorder_msdyn_requirementresourcepreference_WorkOrder](msdyn_workorder.md#BKMK_msdyn_msdyn_workorder_msdyn_requirementresourcepreference_WorkOrder) One-To-Many relationship.

## See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_requirementresourcepreference?text=msdyn_requirementresourcepreference EntityType" />