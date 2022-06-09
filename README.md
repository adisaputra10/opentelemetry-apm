## OpenTelemetry Quickstart
```
curl -s -X POST --cacert config/certs/ca/ca.crt -u elastic:qwerty -H "Content-Type: application/json" http://localhost:9200/_security/user/kibana_system/_password -d "{\"password\":\"qwerty\"}" 

curl -s -X POST   -u elastic:qwerty -H "Content-Type: application/json" http://localhost:9200/_security/user/kibana_system/_password -d "{\"password\":\"qwerty\"}" 
```