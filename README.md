# ![LOGO](logo.png) SqlVirtualMachineManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SqlVirtualMachineManagementClient API (version 2017-03-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/sqlvirtualmachine-sqlvm/2017-03-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:39:14+03:00

## API Description

The SQL virtual machine management API provides a RESTful set of web APIs that interact with Azure Compute, Network & Storage services to manage your SQL Server virtual machine. The API enables users to create, delete and retrieve a SQL virtual machine, SQL virtual machine group or availability group listener.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available SQL Rest API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - API version to use for the request.

### Gets all SQL virtual machine groups in a subscription.

*Tags:* `SqlVirtualMachineGroups`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Gets all SQL virtual machines in a subscription.

*Tags:* `SqlVirtualMachines`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Gets all SQL virtual machine groups in a resource group.

*Tags:* `SqlVirtualMachineGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Deletes a SQL virtual machine group.

*Tags:* `SqlVirtualMachineGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineGroupName` - _required_ - Name of the SQL virtual machine group.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Gets a SQL virtual machine group.

*Tags:* `SqlVirtualMachineGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineGroupName` - _required_ - Name of the SQL virtual machine group.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Updates SQL virtual machine group tags.

*Tags:* `SqlVirtualMachineGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineGroupName` - _required_ - Name of the SQL virtual machine group.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Creates or updates a SQL virtual machine group.

*Tags:* `SqlVirtualMachineGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineGroupName` - _required_ - Name of the SQL virtual machine group.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Lists all availability group listeners in a SQL virtual machine group.

*Tags:* `AvailabilityGroupListeners`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineGroupName` - _required_ - Name of the SQL virtual machine group.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Deletes an availability group listener.

*Tags:* `AvailabilityGroupListeners`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineGroupName` - _required_ - Name of the SQL virtual machine group.
* `availabilityGroupListenerName` - _required_ - Name of the availability group listener.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Gets an availability group listener.

*Tags:* `AvailabilityGroupListeners`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineGroupName` - _required_ - Name of the SQL virtual machine group.
* `availabilityGroupListenerName` - _required_ - Name of the availability group listener.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Creates or updates an availability group listener.

*Tags:* `AvailabilityGroupListeners`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineGroupName` - _required_ - Name of the SQL virtual machine group.
* `availabilityGroupListenerName` - _required_ - Name of the availability group listener.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Gets all SQL virtual machines in a resource group.

*Tags:* `SqlVirtualMachines`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Deletes a SQL virtual machine.

*Tags:* `SqlVirtualMachines`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineName` - _required_ - Name of the SQL virtual machine.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Gets a SQL virtual machine.

*Tags:* `SqlVirtualMachines`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineName` - _required_ - Name of the SQL virtual machine.
* `$expand` - _optional_ - The child resources to include in the response.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Updates a SQL virtual machine.

*Tags:* `SqlVirtualMachines`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineName` - _required_ - Name of the SQL virtual machine.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

### Creates or updates a SQL virtual machine.

*Tags:* `SqlVirtualMachines`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `sqlVirtualMachineName` - _required_ - Name of the SQL virtual machine.
* `subscriptionId` - _required_ - Subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - API version to use for the request.

## License

**flow**ground :- Telekom iPaaS / azure-com-sqlvirtualmachine-sqlvm-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
