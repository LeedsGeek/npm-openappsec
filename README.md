# Nginx Proxy Manager + OpenAppSec
Docker Files for NPM and OpenAppSec both simple model + advanced Models 

# Prerequisites

Docker + Docker Compose
OpenAppSec Account
Ideally DNS name you own 

## For Basic Model (Getting Started)

```bash
npm-openappsec-simple-model.yaml
```
## For Advanced Model (More advanced)
From the OpenAppSec Portal ensure you have download the advanced model from the profile dropdown in the top right. 

```bash
npm-openappsec-advanced-model.yaml
```

## For Advanced Model and Port 81 not exposed
Ensure that you create a proxy host that the portal can be accessed for example: 
FQDN: npm.example.com
scheme: http
forward/IP: 127.0.0.1
Port: 81 

```bash 
npm-openappsec-secure-advanced-model.yaml
```