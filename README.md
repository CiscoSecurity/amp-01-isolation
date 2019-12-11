[![Gitter chat](https://img.shields.io/badge/gitter-join%20chat-brightgreen.svg)](https://gitter.im/CiscoSecurity/AMP-for-Endpoints "Gitter chat")

### AMP for Endpoints [Endpoint Isolation](https://api-docs.amp.cisco.com/api_resources/Endpoint%20Isolation?api_host=api.amp.cisco.com&api_version=v1) Basics:
This collection of scripts cover the basics of interacting with the AMP for Endpoints Endpoint Isolation API. Each script covers one API endpoint. These are intented to show the bare minimum required to interact with the API endpoint.

### Before using you must update the following:
- amp_client_id
- amp_api_key
- computer_guid

### Usage:
```
python 03_endpoint_isolation_put.py
```

### Example script output:
```
{'version': 'v1.2.0', 'metadata': {'links': {'self': 'https://api.amp.cisco.com/v1/computers/d7fbcdb6-0a14-4e39-867e-02f5e1649497/isolation'}}, 'data': {'available': True, 'status': 'pending_start', 'unlock_code': 'gdkxjk', 'comment': None}}
```
