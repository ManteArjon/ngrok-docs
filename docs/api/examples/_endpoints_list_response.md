<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-16T10:05:45Z",
			"hostport": "ea2d14fb1af9.ngrok.paid:443",
			"id": "ep_2qIIDnYvFBrUjNKufLvmVNLalPu",
			"name": "command_line",
			"principal": {
				"id": "usr_2qIIBLZERbkHhZyJiovqQq91riN",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://ea2d14fb1af9.ngrok.paid",
			"tunnel": {
				"id": "tn_2qIIDnYvFBrUjNKufLvmVNLalPu",
				"uri": "https://api.ngrok.com/tunnels/tn_2qIIDnYvFBrUjNKufLvmVNLalPu"
			},
			"tunnel_session": {
				"id": "ts_2qIIDsRQPLnHGuPUJjzVzpEd0hg",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qIIDsRQPLnHGuPUJjzVzpEd0hg"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-16T10:05:45Z",
			"upstream_url": "http://localhost:80",
			"url": "https://ea2d14fb1af9.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-16T10:05:43Z",
			"domain": {
				"id": "rd_2qIIDL9Hv2UQjDjIbRZE41QfBr7",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2qIIDL9Hv2UQjDjIbRZE41QfBr7"
			},
			"edge": {
				"id": "edgtls_2qIIDIqQ9zxTOXuZ3ogwrQaJjmw",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2qIIDIqQ9zxTOXuZ3ogwrQaJjmw"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2qIIDMHaPldvjDXx4qWgyrF40WF",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-16T10:05:43Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
