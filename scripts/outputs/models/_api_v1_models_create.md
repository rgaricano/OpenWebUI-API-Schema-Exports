# /api/v1/models/create

## Table of contents:
- [post](#post)

- [json file](./_api_v1_models_create.json)

---
<a name="post"></a>
## post

**tags:** ['models']

**summary:** Create New Model

**operationId:** create_new_model_api_v1_models_create_post

**requestBody:** {'content': {'application/json': {'schema': {'$ref': '#/components/schemas/ModelForm'}}}, 'required': True}

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'$ref': '#/components/schemas/ModelModel'}, {'type': 'null'}], 'title': 'Response Create New Model Api V1 Models Create Post'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

**security:** [{'HTTPBearer': []}]

