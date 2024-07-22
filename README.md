# Ethical Hacking

> Locating vulnerabilities and weaknesses of computer and information systems by replicating the intent and actions of malicious hackers
> Penetration testing, Red Teaming etc. are other terms for EH.

- **Penetration Test**: Legal attempt to break into a company's network. Pentester only report findings, and does not provide solutions.
- **Security Test**: Includes analyzing company's security policies and principles, and offering solutions, along with Penetration Testing.
- **Hacking**: Showing computer expertise.
- **Cracking**: Breaching software security.
- **Spoofing**: Faking the originating address of a packet.
- **Denial of Service (DOS)**: Flooding a host with network traffic.
- **Port Scanning**: Searching for entry-points that are open.

### Gaining Access

- **Front Door**: Password Guessing / Stealing
- **Back Door**: Entry points often left by the developer for diagnostic tools.
- **Trojan**: Malicious code hidden inside a larger software.
- **Software Vulnerability Exploitation**

### What can they do:
- **Modify logs** to cover their tracks.
- **Steal / Modify Files**
- **Install back doors**
- **Lateral movement**: Attacking other systems.

### Methodologies

1. **Tiger Box**: Collection of OSs and hacking tools
2. **White Box Model**: Knowledge of the entire network is given to the tester.
3. **Black Box Model**: No details about the network is given, and the Hacker has to find the information himself.
4. **Gray Box Model**: Partial Information is given.

```
Overview
--------
- Relevant networking technologies
- Basic cryptographic concepts
- Case studies of secure applications
- Unconventional attacks
- Demonstration of Tools
```

## Networking

> A chain of computers / hosts connected together for communication.

### Data Communication

1. **Circuit Switching**: Establishing a dedicated path for each communication.
    1. Connection Establishment
    2. Data Transfer
    3. Connection Termination
2. **Packet Switching**: All communication links are shared between devices. Data is transmitted as *packets*.
    - *Store and Forward*: Each intermediate recieves the packet, decides the route and forwards the packet.

### Data Transmission

1. **Virtual Circuits**: Similar to circuit switching, where a route is established before transmission. e.g. *Telephone* system.
2. **Datagram**: Each packet is transmitted as an independent entity. Every intermediate node makes dynamic routing decisions.
    - A *Routing Table* is used to determine the optimal path of each packet.

### Delays

- Propagation Delay: Time taken by a data signal to propagate from one node to the next.
- Transmission Delay: Time taken to send out a packet. Depends on the bandwidth of the link.
- Processing Delay: Time taken by a node to process a package.
