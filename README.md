🤎 THE_CYBRARIANS — OCTOBER MONTHLY CHALLENGE

Cisco Networking Lab

Welcome to the October Monthly Challenge!

In this challenge, you will use Cisco Packet Tracer to build, configure and troubleshoot a basic routed network.

⸻

🎯 Objective

Configure the provided network topology, assign the required IP addresses, configure the routers and establish communication between the different networks.

⸻

🛠️ Requirements

Before starting, make sure you have:

* Cisco Packet Tracer
* The provided .pkt starter file
* Basic knowledge of IP addressing and Cisco IOS commands

⸻

🌐 Network Topology

The starter file contains:

* 2 × Cisco 2911 Routers
* 2 × Cisco 2960 Switches
* 3 × PCs

The topology should be:
                                                      
PC0 ─── Switch0 ─── Router0 ─── Router1 ─── Switch1  ─── ( *PC1 AND PC2 SHOULD BE CONNECTED SWITCH 1*)
                                                       
                                                    
                                                      

⸻
## 📋 IP Addressing

### PC0
- IP Address: 192.168.1.2
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.1.1

### PC1
- IP Address: 192.168.2.2
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.2.1

### PC2
- IP Address: 192.168.2.3
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.2.1

### Router0
**G0/0**
- IP Address: 192.168.1.1
- Subnet Mask: 255.255.255.0

**G0/1**
- IP Address: 10.0.0.1
- Subnet Mask: 255.255.255.252

### Router1
**G0/0**
- IP Address: 192.168.2.1
- Subnet Mask: 255.255.255.0

**G0/1**
- IP Address: 10.0.0.2
- Subnet Mask: 255.255.255.252

⸻

🧪 Tasks

Task 1 — Connect the Devices

Connect all devices using the appropriate network cables.

Your completed topology should match the topology shown above.

Task 2 — Configure the PCs

Configure PC0, PC1 and PC2 using the IP addresses, subnet masks and default gateways provided in the addressing table.

Task 3 — Configure Router0

Configure the required interfaces on Router0 using the addressing table.

Ensure that the configured interfaces are enabled and operational.

Task 4 — Configure Router1

Configure the required interfaces on Router1 using the addressing table.

Ensure that the configured interfaces are enabled and operational.

Task 5 — Configure Routing

Configure routing between:

* 192.168.1.0/24
* 192.168.2.0/24

The two networks should be able to communicate through Router0 and Router1.

Task 6 — Test Connectivity

Use the ping command to test connectivity.

At minimum, test:

PC0 → PC1
PC0 → PC2
PC1 → PC0
PC2 → PC0

All required tests should return successful replies.

Task 7 — Troubleshooting

If your connectivity tests fail, check:

* Cable connections
* IP addresses
* Subnet masks
* Default gateways
* Router interfaces
* Interface status
* Routing configuration

⸻

📤 Submission

Submit the following:

1. Completed Packet Tracer File

Upload your completed .pkt file.

2. Topology Screenshot

Take a screenshot showing your completed topology.

3. Connectivity Screenshot

Take a screenshot showing successful ping results.

Submit everything through the official submission form.

⸻

🏆 Scoring

Category	Points
Correct topology	15
Correct cabling	10
PC IP configuration	20
Router interface configuration	20
Routing configuration	20
Successful connectivity tests	15
TOTAL	100

⸻

⚠️ Important

* Do not change the IP addressing plan provided above.
* Make sure all required interfaces are configured correctly.
* Your .pkt file should contain your completed configuration.
* Screenshots should clearly show your work.
* Submissions must be made before the announced deadline.

⸻

🤎 Good luck!

THE_CYBRARIANS
Learn. Build. Secure.
