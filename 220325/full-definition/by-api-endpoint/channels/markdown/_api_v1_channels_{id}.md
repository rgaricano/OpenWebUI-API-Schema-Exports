# /api/v1/channels/{id}

## Table of contents:
- [get](#get)

<a name="get" />
## get

**tags:** ['channels']

**summary:** Get Channel By Id

**operationId:** get_channel_by_id_api_v1_channels__id__get

**security:** [{'HTTPBearer': []}]

**parameters:** [{'name': 'id', 'in': 'path', 'required': True, 'schema': {'type': 'string', 'title': 'Id'}}]

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'$ref': '#/components/schemas/ChannelModel'}, {'type': 'null'}], 'title': 'Response Get Channel By Id Api V1 Channels  Id  Get'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

