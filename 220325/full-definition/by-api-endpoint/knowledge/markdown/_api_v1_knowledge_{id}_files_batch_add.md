# /api/v1/knowledge/{id}/files/batch/add

## Table of contents:
- [post](#post)

<a name="post" />
## post

**tags:** ['knowledge']

**summary:** Add Files To Knowledge Batch

**description:** Add multiple files to a knowledge base

**operationId:** add_files_to_knowledge_batch_api_v1_knowledge__id__files_batch_add_post

**security:** [{'HTTPBearer': []}]

**parameters:** [{'name': 'id', 'in': 'path', 'required': True, 'schema': {'type': 'string', 'title': 'Id'}}]

**requestBody:** {'required': True, 'content': {'application/json': {'schema': {'type': 'array', 'items': {'$ref': '#/components/schemas/KnowledgeFileIdForm'}, 'title': 'Form Data'}}}}

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'$ref': '#/components/schemas/KnowledgeFilesResponse'}, {'type': 'null'}], 'title': 'Response Add Files To Knowledge Batch Api V1 Knowledge  Id  Files Batch Add Post'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

