# /api/v1/chats/

## Table of contents:
- [get](#get)
- [delete](#delete)

<a name="get" />
## get

**tags:** ['chats']

**summary:** Get Session User Chat List

**operationId:** get_session_user_chat_list_api_v1_chats__get

**security:** [{'HTTPBearer': []}]

**parameters:** [{'name': 'page', 'in': 'query', 'required': False, 'schema': {'anyOf': [{'type': 'integer'}, {'type': 'null'}], 'title': 'Page'}}]

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'type': 'array', 'items': {'$ref': '#/components/schemas/ChatTitleIdResponse'}, 'title': 'Response Get Session User Chat List Api V1 Chats  Get'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

<a name="delete" />
## delete

**tags:** ['chats']

**summary:** Delete All User Chats

**operationId:** delete_all_user_chats_api_v1_chats__delete

**security:** [{'HTTPBearer': []}]

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'type': 'boolean', 'title': 'Response Delete All User Chats Api V1 Chats  Delete'}}}}}

