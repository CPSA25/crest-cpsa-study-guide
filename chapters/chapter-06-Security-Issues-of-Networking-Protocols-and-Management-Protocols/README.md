# Chapter 6: Networking Equipment – Management, Monitoring & Device Behaviour

**Alignment:** CREST CPSA Appendix D (Skills D1, D2, D5)  
**Focus:** Management Protocols, Infrastructure Security, and Device Behaviour  
**Exam Weight:** High (Critical for identifying insecure configurations and "backdoor" ports)

## 📖 About This Chapter
While Chapter 5 focused on how data moves (IP/TCP), Chapter 6 focuses on the devices that move it (Routers/Switches) and, critically, **how they are managed**.

For a penetration tester, the "Management Plane" is often the soft underbelly of a network. Finding a router's **Telnet** interface or an exposed **SNMP** string can lead to a full network compromise faster than any exploit. This chapter details the specific protocols used to configure these devices and the inherent vulnerabilities in legacy standards.

## 🎯 Who Is This Chapter For?
*   **Penetration Testers:** Who need to move beyond simple scanning and understand how to compromise the *infrastructure* itself.
*   **Network Engineers:** Who want to secure their management planes against common attacks like SNMP enumeration and VLAN hopping.
*   **CPSA Candidates:** Who need to master **Appendix D**, specifically identifying cleartext protocols (Telnet, HTTP, SNMPv1) and understanding the risks of default configurations.

## 📝 Learning Objectives
By the end of this chapter, you will be able to:
1.  **Identify Insecure Management Protocols:** Distinguish between secure (SSH, SNMPv3, HTTPS) and insecure (Telnet, SNMPv1/v2c, HTTP) protocols and explain the specific risks of cleartext transmission.
2.  **Analyze Infrastructure Vulnerabilities:** Explain how protocols like **CDP** leak intelligence and how **DTP** (Dynamic Trunking Protocol) enables VLAN hopping attacks.
3.  **Understand Routing Security:** Describe the security implications of unauthenticated routing updates in **RIP, OSPF, and BGP** and the concept of "Route Injection."
4.  **Evaluate VoIP Risks:** Deconstruct VoIP infrastructure to identify risks like unencrypted SIP signaling, TFTP configuration downloads, and the separation of Voice VLANs.
5.  **Master Port Identification:** Instantly recognize standard management ports (22, 23, 69, 161, 5060) and "Backdoor" ports like **Reverse Telnet (2001+)**.

## 🗺️ CPSA Syllabus Mapping
This chapter covers the following specific skills from the **CREST CPSA Technical Syllabus (v2.5)**:

| Skill ID | Skill Name | Coverage | CPSA Exam Relevance |
| :--- | :--- | :--- | :--- |
| **D1** | Management Protocols | ✅ Comprehensive | **High** - Frequent MCQs on SNMP versions & Telnet/SSH |
| **D2** | Network Traffic Analysis | ✅ Comprehensive | **Medium** - Focus on Port Mirroring/SPAN & Sniffing |
| **D3** | Networking Protocols | ✅ Comprehensive | **High** - Focus on CDP, STP, and Routing Auth |
| **D5** | VoIP | ✅ Comprehensive | **Medium** - Focus on SIP vs RTP & VLAN Separation |

## 🛠️ Key Concepts Covered
*   **In-Band vs. Out-of-Band Management:** Why separating traffic matters.
*   **SNMP Enumeration:** Community strings (`public`/`private`) and Version differences (v1/v2c vs v3).
*   **Reverse Telnet:** The "Backdoor" vulnerability on ports 2001-20XX.
*   **Routing Protocol Authentication:** Why RIPv1 is dangerous and how OSPF/BGP use MD5.
*   **Layer 2 Attacks:** Understanding the *theory* behind Switch Spoofing (DTP) and Root Bridge Attacks (STP).
*   **VoIP Security:** SIP (Signaling) vs. RTP (Media) and the risk of TFTP config downloads.

## 📚 Recommended Reading
To deepen your understanding of these infrastructure topics, the following resources are recommended:
*   *Network Security Assessment (3rd Edition)* – Chris McNab (Chapter 2: IP Protocols & Chapter 6: Network Devices)
*   *Cisco Guide to Hardening Cisco IOS Devices* – (Official Vendor Documentation)
*   *RFC 2865* – RADIUS Protocol Specification (For understanding the lack of header encryption)

---
*This chapter is part of the open-source **CREST CPSA Study Guide**. Contributions, corrections, and pull requests are welcome!*
