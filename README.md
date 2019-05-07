# ![LOGO](logo.png) ML Team Account Management Client **flow**ground Connector

## Description

A generated **flow**ground connector for the ML Team Account Management Client API (version 2017-05-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/machinelearningexperimentation-machineLearningExperimentation/2017-05-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:19+03:00

## API Description

These APIs allow end users to operate on Azure Machine Learning Team Account resources. They support CRUD operations for Azure Machine Learning Team Accounts.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Azure Machine Learning Team Accounts REST API operations.

*Tags:* `Operation`

#### Input Parameters
* `api-version` - _required_ - The client API version.

### Lists all the available machine learning team accounts under the specified subscription.

*Tags:* `Accounts`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.

### Lists all the available machine learning team accounts under the specified resource group.

*Tags:* `Accounts`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.

### Deletes a machine learning team account.

*Tags:* `Accounts`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.

### Gets the properties of the specified machine learning team account.

*Tags:* `Accounts`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.

### Updates a machine learning team account with the specified parameters.

*Tags:* `Accounts`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.

### Creates or updates a team account with the specified parameters.

*Tags:* `Accounts`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.

### Lists all the available machine learning workspaces under the specified team account.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `accountName` - _required_ - The name of the machine learning team account.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.

### Deletes a machine learning workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.
* `workspaceName` - _required_ - The name of the machine learning team account workspace.

### Gets the properties of the specified machine learning workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.
* `workspaceName` - _required_ - The name of the machine learning team account workspace.

### Updates a machine learning workspace with the specified parameters.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.
* `workspaceName` - _required_ - The name of the machine learning team account workspace.

### Creates or updates a machine learning workspace with the specified parameters.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.
* `workspaceName` - _required_ - The name of the machine learning team account workspace.

### Deletes a project.

*Tags:* `Projects`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.
* `workspaceName` - _required_ - The name of the machine learning team account workspace.
* `projectName` - _required_ - The name of the machine learning project under a team account workspace.

### Gets the properties of the specified machine learning project.

*Tags:* `Projects`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.
* `workspaceName` - _required_ - The name of the machine learning team account workspace.
* `projectName` - _required_ - The name of the machine learning project under a team account workspace.

### Updates a project with the specified parameters.

*Tags:* `Projects`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.
* `workspaceName` - _required_ - The name of the machine learning team account workspace.
* `projectName` - _required_ - The name of the machine learning project under a team account workspace.

### Creates or updates a project with the specified parameters.

*Tags:* `Projects`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.
* `accountName` - _required_ - The name of the machine learning team account.
* `workspaceName` - _required_ - The name of the machine learning team account workspace.
* `projectName` - _required_ - The name of the machine learning project under a team account workspace.

### Lists all the available machine learning projects under the specified workspace.

*Tags:* `Projects`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `accountName` - _required_ - The name of the machine learning team account.
* `workspaceName` - _required_ - The name of the machine learning team account workspace.
* `resourceGroupName` - _required_ - The name of the resource group to which the machine learning team account belongs.

## License

**flow**ground :- Telekom iPaaS / azure-com-machinelearningexperimentation-machine-learning-experimentation-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
