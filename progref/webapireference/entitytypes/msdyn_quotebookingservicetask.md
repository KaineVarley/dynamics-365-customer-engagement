---
title: "Microsoft Dynamics 365 Customer Engagement msdyn_quotebookingservicetask EntityType Reference | MicrosoftDocs"
ms.date: "2017-07-10"
ms.service: "crm-online"
ms.topic: "reference"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: 913bbacc-21f5-4d1d-a7ab-00cccf689327
author: "jimdaly"
ms.author: "jdaly"
manager: "jdaly"
meta-description: "Reference information about the Web API msdyn_quotebookingservicetask entitytype."
---
# msdyn_quotebookingservicetask EntityType
<table>
<tr><td><b>Description:</b></td><td>[!INCLUDE[./descriptions/msdyn_quotebookingservicetask.md](./descriptions/msdyn_quotebookingservicetask.md)]</td></tr>
<tr><td><b>Entity Set path:</b></td><td>[!include[current-web-api-base-uri.md](../includes/current-web-api-base-uri.md)]msdyn_quotebookingservicetasks </td></tr>
<tr><td><b>Base Type:</b></td><td>[crmbaseentity EntityType](crmbaseentity.md)</td></tr>
<tr><td><b>Display Name:</b></td><td>Quote Booking Service Task</td></tr>
<tr><td><b>Primary Key:</b></td><td>msdyn_quotebookingservicetaskid</td></tr>
<tr><td><b>Primary Name Attribute:</b></td><td>msdyn_name</td></tr>
<tr><td><b>Operations supported:</b></td><td>POST,GET,PATCH,DELETE</td></tr>
</table>
  
The msdyn_quotebookingservicetask entitytype has no functions or actions bound to it.

## Properties
Properties represent fields of data stored in the entity. Some properties are read-only. 


|Name|Type|Details|  
|----|----|-------|  
|createdon|Edm.DateTimeOffset|**Display Name**: Created On<br />**Description**: Date and time when the record was created.<br />Read-only<br />|
|importsequencenumber|Edm.Int32|**Display Name**: Import Sequence Number<br />**Description**: Sequence number of the import that created this record.<br />|
|modifiedon|Edm.DateTimeOffset|**Display Name**: Modified On<br />**Description**: Date and time when the record was modified.<br />Read-only<br />|
|msdyn_description|Edm.String|**Display Name**: Description<br />**Description**: Type a description of this quote booking service task.<br />|
|msdyn_estimatedduration|Edm.Int32|**Display Name**: Estimated Duration<br />|
|msdyn_internalflags|Edm.String|**Display Name**: Internal Flags<br />**Description**: Internal use only<br />|
|msdyn_iscopied|Edm.Boolean|**Display Name**: Is Copied<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Yes</td></tr><tr><td>0</td><td>No</td></tr><tbody></table>|
|msdyn_lineorder|Edm.Int32|**Display Name**: Line Order<br />|
|msdyn_name|Edm.String|**Display Name**: Name<br />**Description**: The name of the custom entity.<br />|
|msdyn_quotebookingservicetaskid|Edm.Guid|**Display Name**: Quote Booking Service Task<br />**Description**: Unique identifier for entity instances<br />|
|overriddencreatedon|Edm.DateTimeOffset|**Display Name**: Record Created On<br />**Description**: Date and time that the record was migrated.<br />|
|statecode|Edm.Int32|**Display Name**: Status<br />**Description**: Status of the Quote Booking Service Task<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>0</td><td>Active</td></tr><tr><td>1</td><td>Inactive</td></tr><tbody></table>|
|statuscode|Edm.Int32|**Display Name**: Status Reason<br />**Description**: Reason for the status of the Quote Booking Service Task<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Active</td></tr><tr><td>2</td><td>Inactive</td></tr><tbody></table>|
|timezoneruleversionnumber|Edm.Int32|**Display Name**: Time Zone Rule Version Number<br />**Description**: For internal use only.<br />|
|utcconversiontimezonecode|Edm.Int32|**Display Name**: UTC Conversion Time Zone Code<br />**Description**: Time zone code that was in use when the record was created.<br />|
|versionnumber|Edm.Int64|**Display Name**: Version Number<br />**Description**: Version Number<br />Read-only<br />|

## Lookup Properties
Lookup properties are read-only, computed properties which contain entity primary key Edm.Guid data for one or more corresponding single-valued navigation properties. More information: [Lookup properties](https://msdn.microsoft.com/library/mt607990.aspx#bkmk_lookupProperties) and [Retrieve data about lookup properties](https://msdn.microsoft.com/library/gg334767.aspx#bkmk_lookupProperty).


|Name|Single-valued navigation property|Description|  
|----|---------------------------------|-----------|  
|_createdby_value|createdby<br />|Unique identifier of the user who created the record.|
|_createdonbehalfby_value|createdonbehalfby<br />|Unique identifier of the delegate user who created the record.|
|_modifiedby_value|modifiedby<br />|Unique identifier of the user who modified the record.|
|_modifiedonbehalfby_value|modifiedonbehalfby<br />|Unique identifier of the delegate user who modified the record.|
|_msdyn_customerasset_value|msdyn_customerasset<br />|Unique identifier for Customer Asset associated with Quote Booking Service Task.|
|_msdyn_quote_value|msdyn_quote<br />|Unique identifier for Quote associated with Quote Booking Service Task.|
|_msdyn_quotebookingincident_value|msdyn_quotebookingincident<br />|Shows the quote booking incident associated with the quote booking service task.|
|_msdyn_quotebookingsetup_value|msdyn_QuoteBookingSetup<br />|Unique identifier for Quote Booking Setup associated with Quote Booking Service Task.|
|_msdyn_tasktype_value|msdyn_TaskType<br />|Unique identifier for Service Task Type associated with Quote Booking Service Task.|
|_ownerid_value|ownerid<br />|Owner Id|
|_owningbusinessunit_value|owningbusinessunit<br />|Unique identifier for the business unit that owns the record|
|_owningteam_value|owningteam<br />|Unique identifier for the team that owns the record.|
|_owninguser_value|owninguser<br />|Unique identifier for the user that owns the record.|


## Single-valued navigation properties
Single-valued navigation properties represent lookup fields where a single entity can be referenced. Each single-valued navigation property has a corresponding partner collection-valued navigation property on the related entity.


|Name|Type|Partner|  
|----|----|-------|  
|createdby|[systemuser EntityType](systemuser.md)|lk_msdyn_quotebookingservicetask_createdby|
|createdonbehalfby|[systemuser EntityType](systemuser.md)|lk_msdyn_quotebookingservicetask_createdonbehalfby|
|modifiedby|[systemuser EntityType](systemuser.md)|lk_msdyn_quotebookingservicetask_modifiedby|
|modifiedonbehalfby|[systemuser EntityType](systemuser.md)|lk_msdyn_quotebookingservicetask_modifiedonbehalfby|
|msdyn_customerasset|[msdyn_customerasset EntityType](msdyn_customerasset.md)|msdyn_msdyn_customerasset_msdyn_quotebookingservicetask_CustomerAsset|
|msdyn_quote|[quote EntityType](quote.md)|msdyn_quote_msdyn_quotebookingservicetask_Quote|
|msdyn_quotebookingincident|[msdyn_quotebookingincident EntityType](msdyn_quotebookingincident.md)|msdyn_msdyn_quotebookingincident_msdyn_quotebookingservicetask_QuoteBookingIncident|
|msdyn_QuoteBookingSetup|[msdyn_quotebookingsetup EntityType](msdyn_quotebookingsetup.md)|msdyn_msdyn_quotebookingsetup_msdyn_quotebookingservicetask_QuoteBookingSetup|
|msdyn_TaskType|[msdyn_servicetasktype EntityType](msdyn_servicetasktype.md)|msdyn_msdyn_servicetasktype_msdyn_quotebookingservicetask_TaskType|
|ownerid|[principal EntityType](principal.md)|owner_msdyn_quotebookingservicetask|
|owningbusinessunit|[businessunit EntityType](businessunit.md)|business_unit_msdyn_quotebookingservicetask|
|owningteam|[team EntityType](team.md)|team_msdyn_quotebookingservicetask|
|owninguser|[systemuser EntityType](systemuser.md)|user_msdyn_quotebookingservicetask|

## Collection-valued navigation properties
Collection-valued navigation properties represent collections of entities which may represent either a one-to-many (1:N) or many-to-many (N:N) relationship between the entities.


|Name|Type|Partner|  
|----|----|-------|  
|msdyn_quotebookingservicetask_ActivityPointers|[activitypointer EntityType](activitypointer.md)|regardingobjectid_msdyn_quotebookingservicetask|  
|msdyn_quotebookingservicetask_adx_alertsubscriptions|[adx_alertsubscription EntityType](adx_alertsubscription.md)|regardingobjectid_msdyn_quotebookingservicetask_adx_alertsubscription|  
|msdyn_quotebookingservicetask_adx_inviteredemptions|[adx_inviteredemption EntityType](adx_inviteredemption.md)|regardingobjectid_msdyn_quotebookingservicetask_adx_inviteredemption|  
|msdyn_quotebookingservicetask_adx_portalcomments|[adx_portalcomment EntityType](adx_portalcomment.md)|regardingobjectid_msdyn_quotebookingservicetask_adx_portalcomment|  
|msdyn_quotebookingservicetask_Annotations|[annotation EntityType](annotation.md)|objectid_msdyn_quotebookingservicetask|  
|msdyn_quotebookingservicetask_Appointments|[appointment EntityType](appointment.md)|regardingobjectid_msdyn_quotebookingservicetask_appointment|  
|msdyn_quotebookingservicetask_AsyncOperations|[asyncoperation EntityType](asyncoperation.md)|regardingobjectid_msdyn_quotebookingservicetask|  
|msdyn_quotebookingservicetask_BulkDeleteFailures|[bulkdeletefailure EntityType](bulkdeletefailure.md)|regardingobjectid_msdyn_quotebookingservicetask|  
|msdyn_quotebookingservicetask_connections1|[connection EntityType](connection.md)|record1id_msdyn_quotebookingservicetask|  
|msdyn_quotebookingservicetask_connections2|[connection EntityType](connection.md)|record2id_msdyn_quotebookingservicetask|  
|msdyn_quotebookingservicetask_DuplicateBaseRecord|[duplicaterecord EntityType](duplicaterecord.md)|baserecordid_msdyn_quotebookingservicetask|  
|msdyn_quotebookingservicetask_DuplicateMatchingRecord|[duplicaterecord EntityType](duplicaterecord.md)|duplicaterecordid_msdyn_quotebookingservicetask|  
|msdyn_quotebookingservicetask_Emails|[email EntityType](email.md)|regardingobjectid_msdyn_quotebookingservicetask_email|  
|msdyn_quotebookingservicetask_Faxes|[fax EntityType](fax.md)|regardingobjectid_msdyn_quotebookingservicetask_fax|  
|msdyn_quotebookingservicetask_Letters|[letter EntityType](letter.md)|regardingobjectid_msdyn_quotebookingservicetask_letter|  
|msdyn_quotebookingservicetask_msdyn_approvals|[msdyn_approval EntityType](msdyn_approval.md)|regardingobjectid_msdyn_quotebookingservicetask_msdyn_approval|  
|msdyn_quotebookingservicetask_msdyn_bookingalerts|[msdyn_bookingalert EntityType](msdyn_bookingalert.md)|regardingobjectid_msdyn_quotebookingservicetask_msdyn_bookingalert|  
|msdyn_quotebookingservicetask_msdyn_surveyinvites|[msdyn_surveyinvite EntityType](msdyn_surveyinvite.md)|regardingobjectid_msdyn_quotebookingservicetask_msdyn_surveyinvite|  
|msdyn_quotebookingservicetask_PhoneCalls|[phonecall EntityType](phonecall.md)|regardingobjectid_msdyn_quotebookingservicetask_phonecall|  
|msdyn_quotebookingservicetask_RecurringAppointmentMasters|[recurringappointmentmaster EntityType](recurringappointmentmaster.md)|regardingobjectid_msdyn_quotebookingservicetask_recurringappointmentmaster|  
|msdyn_quotebookingservicetask_ServiceAppointments|[serviceappointment EntityType](serviceappointment.md)|regardingobjectid_msdyn_quotebookingservicetask_serviceappointment|  
|msdyn_quotebookingservicetask_SocialActivities|[socialactivity EntityType](socialactivity.md)|regardingobjectid_msdyn_quotebookingservicetask_socialactivity|  
|msdyn_quotebookingservicetask_SyncErrors|[syncerror EntityType](syncerror.md)|regardingobjectid_msdyn_quotebookingservicetask|  
|msdyn_quotebookingservicetask_Tasks|[task EntityType](task.md)|regardingobjectid_msdyn_quotebookingservicetask_task|  

## Operations
The following operations can be used with the msdyn_quotebookingservicetask entity type.


|Name|Binding|Description|  
|----|-------|-----------|  
|[GrantAccess Action](../actions/grantaccess.md)|Not Bound|[!INCLUDE[../actions/descriptions/grantaccess.md](../actions/descriptions/grantaccess.md)]|  
|[IsValidStateTransition Function](../functions/isvalidstatetransition.md)|Not Bound|[!INCLUDE[../functions/descriptions/isvalidstatetransition.md](../functions/descriptions/isvalidstatetransition.md)]|  
|[ModifyAccess Action](../actions/modifyaccess.md)|Not Bound|[!INCLUDE[../actions/descriptions/modifyaccess.md](../actions/descriptions/modifyaccess.md)]|  
|[RetrievePrincipalAccess Function](../functions/retrieveprincipalaccess.md)|Not Bound|[!INCLUDE[../functions/descriptions/retrieveprincipalaccess.md](../functions/descriptions/retrieveprincipalaccess.md)]|  
|[RetrieveSharedPrincipalsAndAccess Function](../functions/retrievesharedprincipalsandaccess.md)|Not Bound|[!INCLUDE[../functions/descriptions/retrievesharedprincipalsandaccess.md](../functions/descriptions/retrievesharedprincipalsandaccess.md)]|  
|[RevokeAccess Action](../actions/revokeaccess.md)|Not Bound|[!INCLUDE[../actions/descriptions/revokeaccess.md](../actions/descriptions/revokeaccess.md)]|  

## Solutions
The following solutions include the msdyn_quotebookingservicetask entity type.


|Name|Description |  
|----|------------|  
|[Field Service Solution](../solutions/fieldservice.md)|[!INCLUDE[../solutions/descriptions/fieldservice.md](../solutions/descriptions/fieldservice.md)]|    

[!INCLUDE[./remarks/msdyn_quotebookingservicetask.md](./remarks/msdyn_quotebookingservicetask.md)]

### See also  
 [Use the Microsoft Dynamics CRM Web API](https://msdn.microsoft.com/library/mt593051.aspx)<br />
 [Web API EntityType Reference](../entitytypereference.md)<br />
 [Web API Action Reference](../actionreference.md)<br />
 [Web API Function Reference](../functionreference.md)<br />
 [Web API Query Function Reference](../queryfunctionreference.md)<br />
 [Web API EnumType Reference](../enumtypereference.md)<br />
 [Web API ComplexType Reference](../complextypereference.md)<br />
 [Web API Metadata EntityType Reference](../entitytypereference.md)<br />
 [Web API Solutions Reference](../solutionreference.md)<br />