# ![LOGO](logo.png) AutomationManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the AutomationManagement API (version 2018-01-15).

Generated from: https://api.apis.guru/v2/specs/azure.com/automation-dscCompilationJob/2018-01-15/swagger.json<br/>
Generated at: 2019-06-11T18:13:22+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve a list of dsc compilation jobs.

*Tags:* `DscCompilationJob`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `$filter` - _optional_ - The filter to apply on the operation.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Retrieve the Dsc configuration compilation job identified by job id.

*Tags:* `DscCompilationJob`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `compilationJobName` - _required_ - The the DSC configuration Id.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Creates the Dsc compilation job of the configuration.

*Tags:* `DscCompilationJob`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `compilationJobName` - _required_ - The the DSC configuration Id.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Retrieve all the job streams for the compilation Job.

*Tags:* `DscCompilationJob`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobId` - _required_ - The job id.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Retrieve the job stream identified by job stream id.

*Tags:* `DscCompilationJob`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobId` - _required_ - The job id.
* `jobStreamId` - _required_ - The job stream id.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-automation-dsc-compilation-job-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
