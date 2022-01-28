# instahelper-monitoring

### Деплой инфраструктуры

`ansible-playbook deploy_monitoring_scalets_playbook.yaml -e "token=ваш токен"`

### Prometheus
#### Подготовка

```bash
 ansible-galaxy install cloudalchemy.prometheus
 ansible-galaxy install cloudalchemy.node_exporter
```

