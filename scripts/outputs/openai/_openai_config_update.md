# /openai/config/update

## Table of contents:
- [post](#post)

- [json file](./_openai_config_update.json)

---
<a name="post"></a>
## post

**tags:** ['openai']

**summary:** Update Config

**operationId:** update_config_openai_config_update_post

**requestBody:** {'content': {'application/json': {'schema': {'$ref': '#/components/schemas/open_webui__routers__openai__OpenAIConfigForm'}}}, 'required': True}

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

**security:** [{'HTTPBearer': []}]

