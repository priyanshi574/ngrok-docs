<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-04-20T10:06:55Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2vzMnTvFV34zbJzyYlzAaxsA64L",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vzMnTvFV34zbJzyYlzAaxsA64L"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2vzMlyDazQKn67miWAqxshftwiu",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2vzMlyDazQKn67miWAqxshftwiu"
        },
        "enabled": true
      },
      "created_at": "2025-04-20T10:06:43Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2vzMlvMxJKFxlOQT8i0Goyg2lgL",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vzMlvMxJKFxlOQT8i0Goyg2lgL"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
