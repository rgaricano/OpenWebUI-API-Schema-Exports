# /api/v1/chats/{id}/clone/shared

## Table of contents:
- [post](#post)

- [json file](./_api_v1_chats_{id}_clone_shared.json)

---
<a name="post"></a>
## post

**tags:** ['chats']

**summary:** Clone Shared Chat By Id

**operationId:** clone_shared_chat_by_id_api_v1_chats__id__clone_shared_post

**security:** [{'HTTPBearer': []}]

**parameters:** [{'name': 'id', 'in': 'path', 'required': True, 'schema': {'type': 'string', 'title': 'Id'}}]

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'$ref': '#/components/schemas/ChatResponse'}, {'type': 'null'}], 'title': 'Response Clone Shared Chat By Id Api V1 Chats  Id  Clone Shared Post'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

