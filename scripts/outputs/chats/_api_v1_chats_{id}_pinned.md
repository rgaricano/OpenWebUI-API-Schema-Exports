# /api/v1/chats/{id}/pinned

## Table of contents:
- [get](#get)

- [json file](./_api_v1_chats_{id}_pinned.json)

---
<a name="get"></a>
## get

**tags:** ['chats']

**summary:** Get Pinned Status By Id

**operationId:** get_pinned_status_by_id_api_v1_chats__id__pinned_get

**security:** [{'HTTPBearer': []}]

**parameters:** [{'name': 'id', 'in': 'path', 'required': True, 'schema': {'type': 'string', 'title': 'Id'}}]

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'type': 'boolean'}, {'type': 'null'}], 'title': 'Response Get Pinned Status By Id Api V1 Chats  Id  Pinned Get'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

