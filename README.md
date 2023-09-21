# nmra-unpoller
Networkables Monitoring remote agent for UnifFi

Example Run:
```
docker run
  -d --rm
  --name nmra-unpoller
  -e UP_UNIFI_DEFAULT_URL="YOUR_UNIFIOS_URL"
  -e UP_UNIFI_DEFAULT_USER="YOUR_UNIFI_USERNAME"
  -e UP_UNIFI_DEFAULT_PASS="YOUR_UNIFI_PASSWORD"
  -e UP_INFLUXDB_ORG="YOUR_ORG_NAME"
  -e UP_INFLUXDB_AUTH_TOKEN="YOUR_ORG_TOKEN"
 ghcr.io/networkables/nmra-unpoller:1.1.0
 ```
