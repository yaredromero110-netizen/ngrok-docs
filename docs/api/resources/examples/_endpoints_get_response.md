<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "bindings": [
    "public"
  ],
  "created_at": "2025-09-16T10:07:41Z",
  "description": "sample cloud endpoint",
  "domain": {
    "id": "rd_32mEH75alheW57atpGXKCdgIYsc",
    "uri": "https://api.ngrok.com/reserved_domains/rd_32mEH75alheW57atpGXKCdgIYsc"
  },
  "hostport": "endpoint-example2.com:443",
  "id": "ep_32mEHhb5QtrkwZsTIy4UyhkgtPc",
  "metadata": "{\"environment\": \"staging\"}",
  "pooling_enabled": false,
  "proto": "https",
  "public_url": "https://endpoint-example2.com",
  "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
  "type": "cloud",
  "updated_at": "2025-09-16T10:07:41Z",
  "uri": "https://api.ngrok.com/endpoints/ep_32mEHhb5QtrkwZsTIy4UyhkgtPc",
  "url": "https://endpoint-example2.com"
}
```
