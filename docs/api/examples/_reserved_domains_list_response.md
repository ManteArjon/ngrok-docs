<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
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
					"started_at": "2024-12-16T10:05:26Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.fnpfdke57vu9jwyt.local-ngrok-cname.com",
			"created_at": "2024-12-16T10:05:26Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qIIBV3SvLwD6o3ZUk3f28Un8dA",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qIIBV3SvLwD6o3ZUk3f28Un8dA"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2qIIBMOwu4KTKLE84wm7Gj6rEFP",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2qIIBMOwu4KTKLE84wm7Gj6rEFP"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.fnpfdke57vu9jwyt.local-ngrok-cname.com",
			"created_at": "2024-12-16T10:05:25Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qIIBTpnm6gVFAm39mz2Qi9MDQO",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qIIBTpnm6gVFAm39mz2Qi9MDQO"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
