# Lessons Learned

## Overview

Building this enterprise network lab provided practical experience in designing, configuring, testing, and troubleshooting a multi-technology corporate network.

The most important learning was understanding how individual networking technologies work together to form a complete enterprise infrastructure.

---

## 1. Network Design

I learned that successful network implementation begins with proper planning.

Important planning areas include:

* Network topology
* IP addressing
* VLAN structure
* Routing design
* WAN connectivity
* Security policies
* Redundancy
* Documentation

A well-planned network makes configuration and troubleshooting significantly easier.

---

## 2. MikroTik and Cisco Integration

The project provided practical experience integrating:

* MikroTik RouterOS
* Cisco Layer 2 switches
* IEEE 802.1Q VLANs
* Trunk links
* LACP
* Layer 2 and Layer 3 connectivity

This helped strengthen my understanding of interoperability between different network vendors.

---

## 3. VLAN Segmentation

I gained a stronger understanding of how VLANs are used to logically separate enterprise networks.

Key concepts practiced:

* VLAN creation
* Access ports
* Trunk ports
* 802.1Q tagging
* Inter-VLAN routing
* VLAN troubleshooting

VLAN segmentation improves organization, security, and traffic management.

---

## 4. BGP

Implementing dual-ISP connectivity improved my understanding of BGP.

I practiced:

* eBGP
* iBGP
* Autonomous System Numbers
* BGP neighbors
* Route advertisement
* Route filtering
* Routing table verification
* WAN redundancy

The project demonstrated that BGP is not only a configuration task but also a routing-policy mechanism.

---

## 5. LACP

Implementing LACP helped me understand link aggregation in practical scenarios.

I learned how multiple physical links can operate as a logical interface.

Benefits include:

* Increased aggregate bandwidth
* Link redundancy
* Better utilization of multiple physical links

I also learned that both sides of an LACP connection must have compatible configuration and link parameters.

---

## 6. IPsec Site-to-Site VPN

The IPsec implementation provided practical experience with secure branch connectivity.

Important concepts included:

* VPN peers
* IKE negotiation
* Encryption
* Authentication
* Security associations
* Protected networks
* VPN troubleshooting

This demonstrated how organizations can securely connect remote offices across an untrusted network such as the Internet.

---

## 7. GRE Tunnel

The GRE implementation helped me understand logical tunneling between remote networks.

I practiced:

* Tunnel source
* Tunnel destination
* Tunnel addressing
* Routing through the tunnel
* End-to-end connectivity testing

I also learned that GRE itself does not provide encryption, so sensitive traffic may require additional security such as IPsec.

---

## 8. Firewall and NAT

Configuring firewall filtering and NAT improved my understanding of traffic control.

I learned to consider:

* Source address
* Destination address
* Protocol
* Port
* Connection state
* NAT behavior
* Rule order

Firewall troubleshooting also demonstrated the importance of checking counters and traffic flow rather than assuming a configuration is working.

---

## 9. Troubleshooting

One of the most valuable parts of the project was troubleshooting.

I followed a structured approach:

```text
Physical / Interface
        ↓
Layer 2
        ↓
IP Addressing
        ↓
Routing
        ↓
BGP
        ↓
VPN
        ↓
Firewall / NAT
        ↓
End-to-End Testing
```

Instead of changing multiple configurations at once, I learned to isolate the problem layer by layer.

---

## 10. Verification Is Essential

A configuration should not be considered complete simply because the commands were accepted.

I learned to verify:

* Interface status
* VLAN status
* LACP status
* Routing table
* BGP neighbors
* VPN status
* DHCP leases
* NAT translations
* Firewall counters
* Ping
* Traceroute

This helped develop a more operational approach to network engineering.

---

## 11. Documentation

The project reinforced the importance of maintaining proper documentation.

Important documentation includes:

* Network topology
* IP addressing plan
* VLAN plan
* Device configurations
* Verification results
* Troubleshooting records
* Future improvement plans

Good documentation makes a network easier to maintain, troubleshoot, and hand over to another engineer.

---

## 12. Key Takeaways

The major lessons from this project were:

* Design before configuration.
* Understand the traffic flow before troubleshooting.
* Layer 2 problems can look like Layer 3 problems.
* BGP requires careful routing policy.
* VPN connectivity requires verification on both tunnel and routing layers.
* LACP requires compatible configuration on both endpoints.
* Firewall rule order matters.
* Always verify configuration with operational commands.
* Documentation is an essential part of network engineering.

---

## Conclusion

This project significantly improved my practical understanding of enterprise networking.

Rather than studying each technology independently, I learned how **BGP, VLANs, LACP, DHCP, NAT, firewall policies, IPsec, GRE, routing, and switching** interact within a complete enterprise infrastructure.

The experience also strengthened my troubleshooting, documentation, and network design skills and provides a foundation for future work in **network security, automation, and hybrid cloud networking**.
