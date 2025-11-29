<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-09-16T10:07:47Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_32mEIUgjNiBCrDFzlbl7tnTEKyX",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32mEIUgjNiBCrDFzlbl7tnTEKyX"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_32mEH9nqQaBks2rfYliIfFy0l8M",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_32mEH9nqQaBks2rfYliIfFy0l8M"
        },
        "enabled": true
      },
      "created_at": "2025-09-16T10:07:36Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_32mEH7NlkpIurKnruI4xmgLfg9Q",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32mEH7NlkpIurKnruI4xmgLfg9Q"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
