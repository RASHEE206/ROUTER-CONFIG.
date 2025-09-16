# ROUTER-CONFIG.
# ⚙️ Basic Router Configuration on Cisco Packet Tracer
This project focuses on **router setup and configuration** in Cisco Packet Tracer.  
It shows how to assign IP addresses, enable interfaces, and set up basic connectivity.

## 📌 Steps I Took

### 1. Chose a Router
- Used Cisco ISR4331 Router with no GigabitEthernet interfaces.
- Navigated to the physical tab, switched off the router and inserted a NIC card(NIM ES2-4),in order to establish aa connection.
- NB: Not all routers cointain Fast Ethernet or Gig. interface, thus a Network interface card is needed for connectivity.

### 2. Assigned IPs to Interfaces
```bash
Router> enable
Router# configure terminal
Router(config)# interface gigabitethernet0/0/0
Router(config-if)# ip address 192.168.1.1 255.255.255.0
Router(config-if)# no shutdown


