## RADIUS-vs.-TACACS-Network-Security-Protocol-Comparison
### Previously uploaded: _'Enterprise Security Mode'_ https://github.com/ImaneLamriui/Securing-Enterprise-Access, utilizing a RADIUS server for Authentication, Authorization, and Accounting (AAA). Now, let's explore the contrast between _RADIUS and TACACS+_.

__RADIUS__ and __TACACS+__ are both __security protocols for authentication and authorization__ in networks, but they differ in how they handle these functions:

##### Mode of Operation:
__RADIUS__: Operates on a client-server model where network devices send authentication requests to the RADIUS server to verify user credentials.
__TACACS+__: Also follows a client-server model, but divides authentication, authorization, and accounting functions across separate servers for finer control.

##### Security:
__RADIUS__: Uses simpler and less robust encryption compared to TACACS+, potentially making it more vulnerable to attacks.
__TACACS+__: Provides stronger encryption, ensuring higher security in communication between the client and server.

##### Flexibility and Control:
__RADIUS__: Offers basic authentication and authorization, suitable for environments where less detailed control over user access is needed.
__TACACS+__: Provides greater granularity in authorization, allowing for more precise control over actions that authenticated users can perform.

##### Typical Uses:
__RADIUS__: Commonly used in environments where remote user authentication is needed, such as wireless networks or VPN connections.
__TACACS+__: More prevalent in corporate environments where detailed control over user actions is required, such as in the management of critical network devices.

### If we wanted to have centralized management of network devices:
##### - We could implement a RADIUS server or TACACS+ server in the network and configure the network devices to authenticate users. 
##### - We will set up a TACACS authentication server on the network using the Packet Tracer simulator.

<img src="packet-tracer-simulator.png">
