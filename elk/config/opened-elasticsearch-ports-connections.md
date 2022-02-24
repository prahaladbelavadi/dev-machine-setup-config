http:
  port: "9200"
path:
  data: /bitnami/elasticsearch/data
transport:
  tcp:
    port: "9300"
action:
  destructive_requires_name: "true"
network:
  host: 0.0.0.0
  publish_host: 127.0.0.1
  bind_host: 0
node:
  name: ip-172-31-4-40
  master: "true"
  data: "true"
  ingest: "false"
discovery:
  type: single-node
xpack:
  ml:
    enabled: "false"
