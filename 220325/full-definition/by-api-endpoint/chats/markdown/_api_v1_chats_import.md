# /api/v1/chats/import

## Table of contents:
- [post](#post)

<a name="post" />
## post

**tags:** ['chats']

**summary:** Import Chat

**operationId:** import_chat_api_v1_chats_import_post

**requestBody:** {'content': {'application/json': {'schema': {'$ref': '#/components/schemas/ChatImportForm'}}}, 'required': True}

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'$ref': '#/components/schemas/ChatResponse'}, {'type': 'null'}], 'title': 'Response Import Chat Api V1 Chats Import Post'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

**security:** [{'HTTPBearer': []}]

