<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "bindings": [
    "public"
  ],
  "created_at": "2025-04-20T10:06:48Z",
  "description": "Sample Cloud Endpoint",
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
}
