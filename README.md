# ![LOGO](logo.png) QnAMaker Client **flow**ground Connector

## Description

A generated **flow**ground connector for the QnAMaker Client API (version 4.0).

Generated from: https://api.apis.guru/v2/specs/azure.com/cognitiveservices-QnAMaker/4.0/swagger.json<br/>
Generated at: 2019-05-07T17:37:47+03:00

## API Description

An API for QnAMaker Service

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Download alterations from runtime.

*Tags:* `Alterations`

### Replace alterations data.

*Tags:* `Alterations`

### Gets endpoint keys for an endpoint

### Re-generates an endpoint key.

*Tags:* `EndpointKeys`

#### Input Parameters
* `keyType` - _required_ - Type of Key

### Gets all knowledgebases for a user.

*Tags:* `Knowledgebases`

### Asynchronous operation to create a new knowledgebase.

*Tags:* `Knowledgebases`

### Deletes the knowledgebase and all its data.

*Tags:* `Knowledgebases`

#### Input Parameters
* `kbId` - _required_ - Knowledgebase id.

### Gets details of a specific knowledgebase.

*Tags:* `Knowledgebases`

#### Input Parameters
* `kbId` - _required_ - Knowledgebase id.

### Asynchronous operation to modify a knowledgebase.

*Tags:* `Knowledgebases`

#### Input Parameters
* `kbId` - _required_ - Knowledgebase id.

### Publishes all changes in test index of a knowledgebase to its prod index.

*Tags:* `Knowledgebases`

#### Input Parameters
* `kbId` - _required_ - Knowledgebase id.

### Replace knowledgebase contents.

*Tags:* `Knowledgebases`

#### Input Parameters
* `kbId` - _required_ - Knowledgebase id.

### Download the knowledgebase.

*Tags:* `Knowledgebases`

#### Input Parameters
* `kbId` - _required_ - Knowledgebase id.
* `environment` - _required_ - Specifies whether environment is Test or Prod.
    Possible values: Prod, Test.

### Gets details of a specific long running operation.

*Tags:* `Operations`

#### Input Parameters
* `operationId` - _required_ - Operation id.

## License

**flow**ground :- Telekom iPaaS / azure-com-cognitiveservices-qn-a-maker-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
