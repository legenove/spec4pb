### fork from open-api/spec
The object model for OpenAPI specification documents.
Currently supports Swagger 2.0 but add params for protobuf.

```
options:
  request:
    1. forbiden use header params
    2. forbiden duplicate field in path and query and bodys
    3. body must dict
  response:
    1. code, err_msg, response body
```

