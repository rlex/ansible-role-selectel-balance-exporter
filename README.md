Role for managing [selectel balance exporter](https://github.com/xxxcoltxxx/selectel-balance-exporter) for prometheus  

Requires selectel api token to start:
```yaml
selectel_balance_exporter_api_token: your_selectel_api_token
```

Other parameters:
```yaml
selectel_balance_exporter_user: selectel-exporter
selectel_balance_exporter_version: 0.1.7-beta.1
selectel_balance_exporter_listen_address: "0.0.0.0:9600"
selectel_balance_exporter_interval: 3600
selectel_balance_exporter_retry_interval: 10
selectel_balance_exporter_retry_limit: 10
```