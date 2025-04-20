<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-20T10:06:48Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2vzMlu5bg54lVAl1rC0DTDDVZlk",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2vzMlu5bg54lVAl1rC0DTDDVZlk"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2vzMmZdp9m6dJlCNl1gT0FXsodR",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-04-20T10:06:48Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2vzMmZdp9m6dJlCNl1gT0FXsodR",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-20T10:06:47Z",
      "hostport": "04aae0b4eb7b.ngrok.paid:443",
      "id": "ep_2vzMmSCPM9OY2tJ6BBYxFENHW2u",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2vzMjxcTCmRMCtbM0jqS7jQ7uQ7",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://04aae0b4eb7b.ngrok.paid",
      "tunnel": {
        "id": "tn_2vzMmSCPM9OY2tJ6BBYxFENHW2u",
        "uri": "https://api.ngrok.com/tunnels/tn_2vzMmSCPM9OY2tJ6BBYxFENHW2u"
      },
      "tunnel_session": {
        "id": "ts_2vzMmVNjzzLzAWmGKb1QxbVADmN",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2vzMmVNjzzLzAWmGKb1QxbVADmN"
      },
      "type": "ephemeral",
      "updated_at": "2025-04-20T10:06:47Z",
      "upstream_url": "http://localhost:80",
      "url": "https://04aae0b4eb7b.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-20T10:06:44Z",
      "domain": {
        "id": "rd_2vzMlu5bg54lVAl1rC0DTDDVZlk",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2vzMlu5bg54lVAl1rC0DTDDVZlk"
      },
      "edge": {
        "id": "edgtls_2vzMlvMxJKFxlOQT8i0Goyg2lgL",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2vzMlvMxJKFxlOQT8i0Goyg2lgL"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2vzMlt2bXUXYMtlcdej7O0wOKMc",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-04-20T10:06:44Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
