<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vzMnOHndOqBLYweiBvS94Y94Q7","ipp_2vzMnUP5sEeABOwZuhkwYZmtOEi"]}' \
https://api.ngrok.com/edges/tls/edgtls_2vzMnVlyZs0Opbo7q4cx25FKGS3/ip_restriction
