<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"add":{"Content-Security-Policy":"script-src 'self'","X-Frame-Options":"DENY"},"enabled":true}' \
https://api.ngrok.com/edges/https/edghts_2vzMnFkezjsGsReBbz3OUAYWlrI/routes/edghtsrt_2vzMnBuAM8R0VdJT9Vqnj3uKuJq/response_headers
