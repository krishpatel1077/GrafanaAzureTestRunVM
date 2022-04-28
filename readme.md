**KRISH PATEL**
**WPI 2025**
**ELECTRICAL AND COMPUTER ENGINEERING**

All files are from the resource group "grafanatestvm1"

**Purpose:** Run a VM using Azure Marketplace's Grafana Module and display the metrics from Azure Monitor via Grafana Visualization

**Relevant ID's TAGS:
**
**grafanatestvm1.json:** "/subscriptions/9e7e6198-d425-4369-9283-14afde79747c/resourceGroups/grafanatestvm1"
--FILE USED TO CREATE THE ENTIRE RESOURCE GROUP "grafanatestvm1"
**grafana.json:** "/subscriptions/9e7e6198-d425-4369-9283-14afde79747c/resourceGroups/grafanatestvm1/providers/Microsoft.Compute/virtualMachines/grafana"
--FILE USED FOR THE VIRTUAL MACHINE
**grafana-nic.json:** "/subscriptions/9e7e6198-d425-4369-9283-14afde79747c/resourceGroups/grafanatestvm1/providers/Microsoft.Network/networkInterfaces/grafana-nic"
--FILE USED FOR THE GRAFANA NETWORK INTERFACE
**grafana-nsg.json:** "/subscriptions/9e7e6198-d425-4369-9283-14afde79747c/resourceGroups/grafanatestvm1/providers/Microsoft.Network/networkSecurityGroups/grafana-nsg"
--FILE USED FOR THE GRAFANA NETWORK SECURITY GROUP
**grafanaIP.json:** "/subscriptions/9e7e6198-d425-4369-9283-14afde79747c/resourceGroups/grafanatestvm1/providers/Microsoft.Network/publicIPAddresses/grafanaIP"
--FILE USED FOR THE PUBLIC IP THE GRAFANA SERVER IS RAN ON
**grafanaVnet.json: **"/subscriptions/9e7e6198-d425-4369-9283-14afde79747c/resourceGroups/grafanatestvm1/providers/Microsoft.Network/virtualNetworks/grafanaVnet"
--FILE USED FOR THE VIRTUAL NETWORK THAT RUNS THE ENTIRE STRUCTURE


SCREENSHOTS:
![image](https://user-images.githubusercontent.com/40529069/165784447-c5951e6f-25b5-41ce-baae-41c37d847e32.png)
![image](https://user-images.githubusercontent.com/40529069/165784570-429eb4d7-8a07-489b-810b-1e8533b246e4.png)
