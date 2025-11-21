## DNS-DHCP-HTTP-CONFIGRATION
# name:T.DANUSH REDDY
# reg no:212223040029
# Introduction:
Computer networks allow multiple devices to communicate and share information efficiently. In this experiment, three different LAN networks (192.168.10.0/24, 192.168.20.0/24, and 192.168.30.0/24) are interconnected using routers, switches, and PCs.
The purpose of this practical task is to configure the PCs, switches, and routers so that devices across different networks can communicate with each other using proper IP addressing and routing.

This experiment also verifies whether the configured network supports successful end-to-end connectivity using the ping command.

# network diagram:
<img width="1572" height="1013" alt="image" src="https://github.com/user-attachments/assets/fdad3318-120a-411c-a4f7-5680883d6f87" />

# description:
The network contains three LANs, each connected to a router:

| LAN      | Network Address | Default Gateway | PCs                    |
| -------- | --------------- | --------------- | ---------------------- |
| **LAN1** | 192.168.10.0/24 | 192.168.10.1    | PC0 – 10.2, PC1 – 10.3 |
| **LAN2** | 192.168.20.0/24 | 192.168.20.1    | PC2 – 20.2, PC3 – 20.3 |
| **LAN3** | 192.168.30.0/24 | 192.168.30.1    | PC4 – 30.2, PC5 – 30.3 |


Routers are also interconnected using Serial interfaces forming:

* 10.0.0.0/30 (Router0 ↔ Router1)

* 11.0.0.0/30 (Router1 ↔ Router2)

The main goal is to configure:

* 1.Router interfaces with proper IPs

* 2.Static routes so all routers know each other's networks

* 3.PC configurations using correct IP, subnet mask, and gateway

* 4.Testing connectivity using ping
# procedure:
# output:
All PC IP-confrations:
<img width="541" height="367" alt="image" src="https://github.com/user-attachments/assets/43889710-d0e9-4977-b634-10c6c5c33a7d" />

<img width="542" height="356" alt="image" src="https://github.com/user-attachments/assets/174ff855-1eaf-4d7e-acd4-4758bf62a999" />

<img width="542" height="367" alt="image" src="https://github.com/user-attachments/assets/d683fd66-e7ae-4d78-b971-0ac871ea3c36" />

All  successful ping connections:

<img width="545" height="367" alt="image" src="https://github.com/user-attachments/assets/328878fb-932d-44f4-a97b-5c11d35c58e2" />


# result
