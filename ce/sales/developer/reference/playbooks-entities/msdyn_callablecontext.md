---
title: "msdyn_callablecontext EntityType | MicrosoftDocs"
description: "As developer, use this reference information to understand the msdyn_callablecontext EntityType and its properties."
ms.date: 04/08/2019
ms.topic: article
author: lavanyakr01
ms.author: lavanyakr
manager: shujoshi
---
# msdyn_callablecontext EntityType 

As developer, use this reference information to understand the msdyn_callablecontext EntityType and its properties.

## License and role requirements
| Requirement type | You must have |  
|-----------------------|---------|
| **License** | Dynamics 365 Sales Premium or Dynamics 365 Sales Enterprise  <br>More information: [Dynamics 365 Sales pricing](https://dynamics.microsoft.com/sales/pricing/) |
| **Security roles** | System customizer <br>  More information: [Predefined security roles for Sales](../../../security-roles-for-sales.md)|


## Entity details

[!INCLUDE[msdyn_callablecontext-description](../includes/msdyn_callablecontext-description.md)]

Entity set path: `[organizationURI]/api/data/v9.1/msdyn_callablecontexts`<br />
Display name: Playbook calling record type <br />
Primary key: msdyn_callablecontextid <br />
Operations supported: Create, retrieve, update, and delete<br />

## Properties

Properties represent fields of data stored in the entity. Some properties are read-only.

|Name|Display name|Type|Description|
|-----|-----|-----|-----|
|createdby|Created By|Edm.Guid|Unique identifier of the user who created the record.|
|createdon|Created On|Edm.DateTimeOffset|Date and time the record was created.|
|createdonbehalfby|CreatedOnBehalfBy|Edm.Guid|Unique identifier of the delegate user who created the record.|
|importsequencenumber|Import Sequence Number|Edm.Int32|Sequence number of the import that created this record.|
|modifiedby|Modified By|Edm.Guid|Unique identifier of the user who modified the record.|
|modifiedon|Modified On|Edm.DateTimeOffset|Date and time when the record was modified.|
|modifiedonbehalfby|Modified On Behalf By|Edm.Guid|Unique identifier of the delegate user who modified the record.|
|msdyn_callablecontextid|Playbook calling record type|Edm.Guid|Unique identifier for entity instances.|
|msdyn_EntityLogicalName|Name|Edm.String|The name of the custom entity.|
|msdyn_EntityOTC|Fiscal Year|Edm.Int32|Internal use only.|
|overriddencreatedon|Record Created On|Edm.DateTimeOffset|Date and time that the record was migrated.|
|owner|Owner|Edm.Guid|Owner ID.|
|owningbusinessunit|Owning Business Unit|Edm.Guid|Unique identifier for the business unit that owns the record.|
|owningteam|Owning Team|Edm.Guid|Unique identifier for the team that owns the record.|
|owninguser|Owning User|Edm.Guid|Unique identifier for the user who owns the record.|
|statecode|Status|Edm.Int32|Status of the Playbook Callable Context|
|statuscode|Status reason|Edm.Int32|Reason for the status of the Playbook Callable Context.|
|timezoneruleversionnumber|Time Zone Rule Version Number|Edm.Int32|For internal use only.|
|utcconversiontimezonecode|UTC Conversion Time Zone Code|Edm.Int32|Time zone code that was in use when the record was created.|
|versionnumber|Version Number|Edm.Int64|Version number.|

### See also

[Entity reference for playbooks](../playbook-entity-reference.md)


[!INCLUDE[footer-include](../../../../includes/footer-banner.md)]
