# Lab-5---VLAN-configuration
In this lab, I configure two separate VLANS and a trunkport
1. To start, All PC's were by default in VLAN 1, so they could interact with eachother via switch
2. Logically seperated the 4 PC's in two groups of two, PC1 and PC3 assgined to VLAN 1 and PC3 and PC4, assigned to VLAN 2
3. PC3 and PC4 still couldnt interact because the link between the switches were by default VLAN 1
4. Configured the switched link as trunkport to carry traffic for both VLAN's
5. Now PC's can only interact with PC's in same VLAN
