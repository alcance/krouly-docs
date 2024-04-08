---
sidebar_position: 1
---

# Create a Playbook

Create a YAML file called `krouly.sample.yml` inside the `playbooks/` folder with the following code:

```yaml
playbook: Yahoo Finance Crypto Connector
tasks:
  - name: Extract Crypto Data from Yahoo Finance
    connector: KroulyYahooCryptoConnector
    parameters:
      url: https://finance.yahoo.com/crypto

```

> Auto-discovery for files will be added in coming version and multiple playbook support.