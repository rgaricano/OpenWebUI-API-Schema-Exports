# /api/v1/tools/id/{id}/valves/user/spec

## Table of contents:
- [get](#get)

- [json file](./_api_v1_tools_id_{id}_valves_user_spec.json)

---
<a name="get"></a>
## get

**tags:** ['tools']

**summary:** Get Tools User Valves Spec By Id

**operationId:** get_tools_user_valves_spec_by_id_api_v1_tools_id__id__valves_user_spec_get

**security:** [{'HTTPBearer': []}]

**parameters:** [{'name': 'id', 'in': 'path', 'required': True, 'schema': {'type': 'string', 'title': 'Id'}}]

**responses:** {'200': {'description': 'Successful Response', 'content': {'application/json': {'schema': {'anyOf': [{'type': 'object'}, {'type': 'null'}], 'title': 'Response Get Tools User Valves Spec By Id Api V1 Tools Id  Id  Valves User Spec Get'}}}}, '422': {'description': 'Validation Error', 'content': {'application/json': {'schema': {'$ref': '#/components/schemas/HTTPValidationError'}}}}}

