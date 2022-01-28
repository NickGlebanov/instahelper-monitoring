# instahelper-monitoring

### Деплой инфраструктуры

`ansible-playbook deploy_monitoring_scalets_playbook.yaml -e "token=55d43e535445b40b410c950c5f35973d73006a7e19e788bde47b613efca4fb5c"`

### Prometheus
#### Подготовка

```bash
 ansible-galaxy install cloudalchemy.prometheus
 ansible-galaxy install cloudalchemy.node_exporter
```
