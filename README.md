Albion University Network Design

This project is a network design and implementation for Albion University, a large university with two campuses. The network is designed to support four faculties and various departments by using a structured topology with routers, switches, and servers. The main goal is to create a functional network that provides end-to-end connectivity, access to internal and external servers, and meets specific security and routing requirements.

Topology

The Albion University network topology is designed to interconnect two separate campuses. The main campus consists of three buildings, and a smaller campus supports a single faculty. The core architecture is based on routers and switches to segment and secure the network.
<img width="1548" height="621" alt="DIAGRAM TOPOLOGY" src="https://github.com/user-attachments/assets/df2eb6fd-6174-4ec8-bebf-225a3938fb10" />

Topology Details:

Main Campus:
Building A: Houses administrative staff from management, HR, and finance departments, as well as the Faculty of Business. VLANs are expected to be used here to segment the staff PCs.
Building B: Houses the Faculty of Engineering and Computing and the Faculty of Art and Design.
Building C: Contains the students' labs and the IT department. The IT department hosts the University's internal Web server and other servers.

Smaller Campus:
Houses the Faculty of Health and Sciences, with staff and student labs located on separate floors.

External Servers: The university's email server is hosted externally on the cloud.

Requirements Met

✅ Network Segmentation: Each department and faculty is to be on its own separate IP network.
✅ VLANs & Security: Switches will be configured with appropriate VLANs and security settings.
✅ Internal Routing: The RIPv2 routing protocol will be used to provide routing for the internal network.
✅ External Routing: Static routing will be used to provide connectivity to the external email server.
✅ DHCP: Devices in Building A will get their IP addresses dynamically from a router-based DHCP server.
✅ End-to-End Connectivity: The core devices and a few end devices are configured to provide full connectivity to both internal and external servers.

How to run the project
This project is a Cisco Packet Tracer file. To run it, you'll need the software installed on your machine.

Clone this repository to your local machine.

Open the .pkt file in Cisco Packet Tracer.

Explore the topology and configurations to understand how each requirement was implemented.
