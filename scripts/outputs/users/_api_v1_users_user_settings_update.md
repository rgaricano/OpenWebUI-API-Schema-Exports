# /api/v1/users/user/settings/update

## Table of contents:
- [post](#post)

- [json file](./_api_v1_users_user_settings_update.json)

---
<a name="post"></a>
## post

**tags:** ['users']

**summary:** Update User Settings By Session User

**operationId:** update_user_settings_by_session_user_api_v1_users_user_settings_update_post

**requestBody:** {'content': {'application/json': {'schema': {'$ref': '#/components/schemas/UserSettings'}}}, 'required': True}

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/UserSettings'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

**security:** [{'HTTPBearer': []}]

