# SONiC-telemetry setup

Step-by-Step procedure: </br>
</br>
1-
From SONiC Device point of view you need 2 actions:
- 1.1 install telegraf      on SONiC (debian) subsystem 
- 1.2 install node_exporter on SONiC (debian) subsystem

2-
Create an Ubuntu Virtual machine with "good amount" of cpu/ram
- 2.1 install prometheus on Ubuntu (standard procedure)
  - copy prometheusv2.yml under /etc/prometheus/
  - file is available in this repo on /src/
- 2.2 install grafana on Ubuntu (standard procedure)

3-
Configure the different aspect of the Grafana/Prometheus dashboard
- 3.1 install grafana dashboard (readme file under "src/grafana" folder)

[go to src file](#/src/)



![architecture](https://user-images.githubusercontent.com/20860769/207547949-72f24b28-2438-46b5-9dc5-5145bd08a5b3.jpg)
