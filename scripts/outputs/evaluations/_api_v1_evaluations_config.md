# /api/v1/evaluations/config

## Table of contents:
- [get](#get)

- [post](#post)

- [json file](./_api_v1_evaluations_config.json)

---
<a name="get"></a>
## get

**tags:** ['evaluations']

**summary:** Get Config

**operationId:** get_config_api_v1_evaluations_config_get

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {}}}}}

**security:** [{'HTTPBearer': []}]

<a name="post"></a>
## post

**tags:** ['evaluations']

**summary:** Update Config

**operationId:** update_config_api_v1_evaluations_config_post

**requestBody:** {'content': {'application/json': {'schema': {'$ref': '#/components/schemas/UpdateConfigForm'}}}, 'required': True}

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

**security:** [{'HTTPBearer': []}]

