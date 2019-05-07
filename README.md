# ![LOGO](logo.png) RecoveryServicesClient **flow**ground Connector

## Description

A generated **flow**ground connector for the RecoveryServicesClient API (version 2016-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/recoveryservices-vaultusages/2016-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:39+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Fetches the usages of the vault.

*Tags:* `VaultUsages`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

## License

**flow**ground :- Telekom iPaaS / azure-com-recoveryservices-vaultusages-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
