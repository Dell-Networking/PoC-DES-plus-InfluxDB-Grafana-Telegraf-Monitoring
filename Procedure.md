# SONiC-telemetry setup

Step-by-Step procedure: </br>
</br>
1-
From SONiC Device point of view you need 2 actions:
- 1.1 install telegraf      on SONiC (debian) subsystem 
- 1.2 install node_exporter on SONiC (debian) subsystem

2-
Create an Ubuntu Virtual machine with "good amount" of cpu/ram
- 2.1 install prometheus on Ubuntu
  -> copy prometheus.yml under /etc/prometheus/
  - file under/files/
- 2.2 install grafana on Ubuntu

3-
Configure the different aspect of the Grafana/Prometheus dashboard
- 3.1 install grafana dashboard (readme file under "files" folder)
