# moinitoring-prometheus

Config prometheus.yml demo
```
  - job_name: 'apps-node-exporter'
    scrape_interval: 5s
    static_configs:
    - targets: ['[domain or host ip]:[port]']
      labels:
        service: 'apps labels 1'

  - job_name: 'apps-cadvisor'
    scrape_interval: 5s
    static_configs:
    - targets: ['[domain or host ip]:[port]']
      labels:
        service: 'apps labels 2'
```
