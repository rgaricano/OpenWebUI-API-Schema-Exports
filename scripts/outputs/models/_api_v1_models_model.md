# /api/v1/models/model

## Table of contents:
- [get](#get)

- [json file](./_api_v1_models_model.json)

---
<a name="get"></a>
## get

**tags:** ['models']

**summary:** Get Model By Id

**operationId:** get_model_by_id_api_v1_models_model_get

**security:** [{'HTTPBearer': []}]

**parameters:** [{'name': 'id', 'in': 'query', 'required': True, 'schema': {'type': 'string', 'title': 'Id'}}]

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'$ref': '#/components/schemas/ModelResponse'}, {'type': 'null'}], 'title': 'Response Get Model By Id Api V1 Models Model Get'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

