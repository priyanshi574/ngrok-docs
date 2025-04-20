<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vzMnPzQ3CN5Yk0HogL6fGR1t8X"]}' \
https://api.ngrok.com/edges/tcp/edgtcp_2vzMnRjvZSjJkfPgGKqx9S1Ojig/ip_restriction
