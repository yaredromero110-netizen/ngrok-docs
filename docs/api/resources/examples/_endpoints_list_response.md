<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
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
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-16T10:07:39Z",
      "hostport": "9728aea0da45.ngrok.paid:443",
      "id": "ep_32mEHY1eZlNqae0ww7vttcrqBcm",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_32mEAmkMnH1ePhH9D3GiddoxEHP",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://9728aea0da45.ngrok.paid",
      "tunnel": {
        "id": "tn_32mEHY1eZlNqae0ww7vttcrqBcm",
        "uri": "https://api.ngrok.com/tunnels/tn_32mEHY1eZlNqae0ww7vttcrqBcm"
      },
      "tunnel_session": {
        "id": "ts_32mEHXYJfKIE1aHX7akHWZPOhSW",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_32mEHXYJfKIE1aHX7akHWZPOhSW"
      },
      "type": "ephemeral",
      "updated_at": "2025-09-16T10:07:39Z",
      "upstream_url": "http://localhost:80",
      "url": "https://9728aea0da45.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-16T10:07:37Z",
      "domain": {
        "id": "rd_32mEH75alheW57atpGXKCdgIYsc",
        "uri": "https://api.ngrok.com/reserved_domains/rd_32mEH75alheW57atpGXKCdgIYsc"
      },
      "edge": {
        "id": "edgtls_32mEH7NlkpIurKnruI4xmgLfg9Q",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_32mEH7NlkpIurKnruI4xmgLfg9Q"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_32mEH4sXD80lYgjUzEDXjxWjw4P",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-09-16T10:07:37Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
