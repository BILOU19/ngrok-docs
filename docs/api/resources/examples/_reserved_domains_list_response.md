<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2lCrT5xK7YNuXlTVizkEeC4qa4e",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2lCrT5xK7YNuXlTVizkEeC4qa4e"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.5iwxxgtrcp24vuw9s.local-ngrok-cname.com",
			"created_at": "2024-08-26T17:55:03Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2lCrTAMIHpDcj6OGuBGxDdPSpCY",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2lCrTAMIHpDcj6OGuBGxDdPSpCY"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2024-08-26T17:55:04Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.5iwxxgtrcp24vuw9s.local-ngrok-cname.com",
			"created_at": "2024-08-26T17:55:04Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2lCrT9I22Mt98xOZOyKKvPSY1KI",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2lCrT9I22Mt98xOZOyKKvPSY1KI"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
