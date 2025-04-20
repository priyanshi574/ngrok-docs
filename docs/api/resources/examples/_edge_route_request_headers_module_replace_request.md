<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"add":{"x-frontend":"ngrok"},"enabled":true,"remove":["cache-control"]}' \
https://api.ngrok.com/edges/https/edghts_2vzMnAa62kP9Vwq6F0KAJI4H9Zd/routes/edghtsrt_2vzMnFT8PIfJ60PlvFPpds84bTf/request_headers
