Tools:  Promtail, Loki, Grafana

- What discovery mechanism does Promtail support?
    - https://grafana.com/docs/loki/latest/clients/promtail/#log-file-discovery
- I want to push logs to Loki
    - https://grafana.com/docs/loki/latest/api/#post-lokiapiv1push
    - https://medium.com/geekculture/pushing-logs-to-loki-without-using-promtail-fc31dfdde3c6
- I want to change discovery pod label for promtail
    - https://grafana.com/docs/loki/latest/clients/promtail/configuration/#relabel_configs
- I want to add information like label in a log line based on the content
    - https://grafana.com/docs/loki/latest/clients/promtail/pipelines/
- The promtail instance suddenly stops. How does it know where to continue?
    - https://grafana.com/docs/loki/latest/clients/promtail/#shipping
- 