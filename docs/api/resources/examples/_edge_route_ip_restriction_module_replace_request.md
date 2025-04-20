<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vzMn2T5vdc6oNUhE33t2uIfQYg","ipp_2vzMn2D64GTQkxvIx0D4XYshcGp"]}' \
https://api.ngrok.com/edges/https/edghts_2vzMn3J90bpHzhQttWZkMzfeuuP/routes/edghtsrt_2vzMn3Ktb7IRzlcy6SIfk2HS1lO/ip_restriction
