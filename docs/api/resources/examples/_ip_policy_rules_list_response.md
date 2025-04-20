<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "ip_policy_rules": [
    {
      "action": "allow",
      "cidr": "2.2.2.2/32",
      "created_at": "2025-04-20T10:06:49Z",
      "description": "alan laptop",
      "id": "ipr_2vzMmkknAzdgzfZXGoBdcWN639f",
      "ip_policy": {
        "id": "ipp_2vzMmhmtYwGhLoWyPCGv3hIkGBC",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2vzMmhmtYwGhLoWyPCGv3hIkGBC"
      },
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2vzMmkknAzdgzfZXGoBdcWN639f"
    },
    {
      "action": "allow",
      "cidr": "132.2.19.0/24",
      "created_at": "2025-04-20T10:06:49Z",
      "description": "sf office",
      "id": "ipr_2vzMmiK0ElmvbdGsfCeiffy9Mub",
      "ip_policy": {
        "id": "ipp_2vzMmhmtYwGhLoWyPCGv3hIkGBC",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2vzMmhmtYwGhLoWyPCGv3hIkGBC"
      },
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2vzMmiK0ElmvbdGsfCeiffy9Mub"
    },
    {
      "action": "allow",
      "cidr": "212.3.14.0/24",
      "created_at": "2025-04-20T10:06:49Z",
      "description": "nyc office",
      "id": "ipr_2vzMmfpDwkCTkfsoRG2Ukmbs4s0",
      "ip_policy": {
        "id": "ipp_2vzMmhmtYwGhLoWyPCGv3hIkGBC",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2vzMmhmtYwGhLoWyPCGv3hIkGBC"
      },
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2vzMmfpDwkCTkfsoRG2Ukmbs4s0"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/ip_policy_rules"
}
