# node-red-epson-plotter

On my work we have a new Epson SC-T5700 Plotter and I monitor the Ink fill stands with
Node-Red and Grafana.

Here are the Flows and the Grafana Dasboard.

## Dependencies:

[node-red-node-snmp](https://flows.nodered.org/node/node-red-node-snmp)

[node-red-contrib-influxdb](https://flows.nodered.org/node/node-red-contrib-influxdb)

A Working Influx Database

A Working Grafana Installation

## Workflow

Node-Red read over the SNMP Protocol the fill stands of every Inkcartidge and write it into an InfluxDB

Grafana read the InfluxDB and visualized the values as gauge. 

There are some thresholds deposit, if the filling level falls below 10%.


## Node Red-Flow

![Node-Red-Epson](https://github.com/user-attachments/assets/a5f746a0-a818-4cb1-9c09-b6b5404535aa)

## Grafana
![Zwischenablage_11-13-2024_01](https://github.com/user-attachments/assets/a5ae9fdc-a14a-4b61-a3c7-debc4fe15ffd)




-------------------------------------------



Greetings Torsten





