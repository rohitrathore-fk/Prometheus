# Prometheus
Run `docker compose up` <br> 
Prometheus will be on `localhost:9090`<br>
Alertmanager will be on `localhost:9093`<br>
Node-exporter will be on `localhost:9100`<br>
<br>
`alertmanager/alertmanager.yml` has user groups to which email will be sent when any of the prometheus targets go down. Can be checked by shutting down node-exporter and then alerts will be sent to respective email groups.
