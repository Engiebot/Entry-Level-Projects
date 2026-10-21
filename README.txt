Santiaguel, Generoso Jr. P.

Network Fundamentals · Cisco Packet Tracer · Wireshark
Systems Support  · Diagnosing · Troubleshooting · Resource Monitor · Crash Logs Debugging (WinDbg)

I am a Network & Systems Associate skilled in technical troubleshooting and isolating hardware and software faults. As a continuous learner, I am actively expanding my knowledge of broad network infrastructure.

📍 Tanza, Cavite, Philippines · ✉️ generososantiaguel4@gmail.com

Open to entry-level IT Support/Helpdesk and Junior networking roles.

Technical Project Highlights
Cisco Packet Tracer · Network Topology Design

Independent technical project

Designed a network topology integrating two subnetworks · In progress.
Configured Hot Standby Router Protocol (HSRP) for default gateway redundancy.
 - Cisco Packet Tracer topology with two subnetworks and HSRP gateway redundancy
 - Technical Troubleshooting & Problem-Solving

1. KERNEL AND DRIVER CRASH ANALYSIS

Symptom		:	Recurring Windows graphics crashes while playing Valorant.
Ruled out	:	A reinstall and an OS update rollback.
Method		:	Reviewed Event Viewer logs, then analyzed the crash with WinDbg.
Finding		:	Conflicting graphics drivers.
Fix			:	Fully removed the iGPU drivers and let a clean driver install take over.

2. NETWORK CONNECTIVITY DIAGNOSTICS	
Symptom		:	Internet dropouts while the device still showed "connected".
Method		:	Pinged the default gateway first, then the DNS server.
Finding		:	The fault sat with the ISP-side DNS, not the local network.

3. NETWORK VARIABLE ISOLATION
Symptom		:	An account could not be created and could not log in.
Method		:	Tested the device, the email, and the network as three separate variables.
Finding		:	A network-level restriction was blocking the account.
Fix			:	Temporarily used a different local area network to proceed.

4. LATENCY SOURCE TRACING
Symptom		:	High ping to Service A, while Service B stayed normal.
Ruled out	:	Packet drops inside my own network (checked in Wireshark).
Method		:	Ran tracert to the server IP of each service and compared the hops.
Finding		:	The delay built up at the 20th hop, beyond my local network.

Working knowledge of where firewalls sit, how they inspect traffic, and how a DMZ separates public services from the internal network.

Concept			What it means
Stateless	:	Checks each packet on its own against rules for address, port and protocol. It keeps no memory of connections, so return traffic needs its own rule.
Stateful	:	Keeps a table of active sessions and allows replies to traffic started from the trusted side, without a separate inbound rule.
Edge router	:	Sits between the internet and the organization. Combines stateful filtering with application awareness and threat inspection at the network edge.
ISFW		:	Placed inside the network to separate segments from each other, so a problem in one zone has a harder time reaching the rest.
				Note: Both Edge router and ISFW can be NGFW.
DMZ			:	A separate zone for public-facing servers. Internet traffic can reach them, but not the internal network behind them.

Local Cisco Packet Tracer Project  [https://github.com/Engiebot/Entry-Level-Projects/blob/main/Local%20Project%20(Network)%20-%20In%20progress.png]

Skills
Cisco Packet Tracer  · Network diagnostics · System Hardware and Software diagnostics · System Hardware and Software Troubleshooting ·  Crash Logs 
