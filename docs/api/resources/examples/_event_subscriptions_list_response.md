<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-04-20T10:06:50Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_2vzMmmj78680NVcdFWCAMa0FXWf",
          "uri": "https://api.ngrok.com/event_destinations/ed_2vzMmmj78680NVcdFWCAMa0FXWf"
        }
      ],
      "id": "esb_2vzMmqlHxeXIbdHroDKB2K73gha",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2vzMmqlHxeXIbdHroDKB2K73gha/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2vzMmqlHxeXIbdHroDKB2K73gha"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
