# /api/v1/knowledge/{id}/reset

## Table of contents:
- [post](#post)

<a name="post" />
## post

**tags:** ['knowledge']

**summary:** Reset Knowledge By Id

**operationId:** reset_knowledge_by_id_api_v1_knowledge__id__reset_post

**security:** [{'HTTPBearer': []}]

**parameters:** [{'name': 'id', 'in': 'path', 'required': True, 'schema': {'type': 'string', 'title': 'Id'}}]

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'$ref': '#/components/schemas/KnowledgeResponse'}, {'type': 'null'}], 'title': 'Response Reset Knowledge By Id Api V1 Knowledge  Id  Reset Post'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

