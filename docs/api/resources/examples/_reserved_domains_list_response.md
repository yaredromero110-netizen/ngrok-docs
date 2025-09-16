<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-09-16T10:07:21Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.2i3hqqpwl1et7dg2j.local-ngrok-cname.com",
      "created_at": "2025-09-16T10:07:21Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32mEFITD8JsXl7a1sagvUsagAzm",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32mEFITD8JsXl7a1sagvUsagAzm"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_32mEF8mrWNywh0Wl9n1kHloTFD9",
        "uri": "https://api.ngrok.com/tls_certificates/cert_32mEF8mrWNywh0Wl9n1kHloTFD9"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.2i3hqqpwl1et7dg2j.local-ngrok-cname.com",
      "created_at": "2025-09-16T10:07:20Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32mEFGpQyRqi8aHeaqk3OZbzv1H",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32mEFGpQyRqi8aHeaqk3OZbzv1H"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-09-16T10:06:50Z",
      "description": "Your dev domain",
      "domain": "monoeciously-demiurgeous-sheldon.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32mEBItLU6WAC9hYq4eHEUpElFe",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32mEBItLU6WAC9hYq4eHEUpElFe"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
