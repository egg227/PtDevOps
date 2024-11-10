# PtDevOps


### Ansible

`./start.sh`

в inventory.ini свой хост и ssh-ключ

### CI/CD

`docker build -t healthz .`

`docker run -d -p 8000:8000 healthz`

### Monitoring

[blackbox exporter](monitoring/blackbox.yml)

[prometheus](monitoring/prometheus.yml)