
#### Example Request
```bash
curl \
-XPATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"point-of-sale new york #302","metadata":"{env: \"staging\", \"connector_id\":\"64698fcc-5f5c-4b63-910e-8669d04bd943\"}","http_endpoint_configuration_id":"ec_2IEh2Gaj46c9IISa4Ee4PYqgVIb","https_endpoint_configuration_id":"ec_2IEh2G9OAyocwnMOzWc8MjY15QH","certificate_management_policy":{"authority":"letsencrypt"}}' \
https://api.ngrok.com/reserved_domains/rd_2IEh2HHiRNaJknCfX8LjcIskC4V
