# /api/v1/tools/id/{id}/update

## Table of contents:
- [post](#post)

- [json file](./_api_v1_tools_id_{id}_update.json)

---
<a name="post"></a>
## post

**tags:** ['tools']

**summary:** Update Tools By Id

**operationId:** update_tools_by_id_api_v1_tools_id__id__update_post

**security:** [{'HTTPBearer': []}]

**parameters:** [{'name': 'id', 'in': 'path', 'required': True, 'schema': {'type': 'string', 'title': 'Id'}}]

**requestBody:** {'required': True, 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/ToolForm'}}}}

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'$ref': '#/components/schemas/ToolModel'}, {'type': 'null'}], 'title': 'Response Update Tools By Id Api V1 Tools Id  Id  Update Post'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

