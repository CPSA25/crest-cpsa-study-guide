# Chapter 5: Core Technical Skills – The Foundation of the Network

**Alignment:** CREST CPSA Appendix B (Skills B1 & B2)  
**Focus:** IP Protocols, Network Architecture, and The TCP/IP Stack  
**Exam Weight:** High (15-20% of Technical Questions)

## 📖 About This Chapter
This chapter marks the transition from "Management & Legal" (Chapters 1-4) into the **Technical Syllabus**. It covers the fundamental networking knowledge that every penetration tester must master before running a single tool.

In the CPSA exam, you won't just be asked "What is port 80?" You will be asked to identify a specific operating system based on its **TCP Window Size** or explain why a **FIN packet** elicits a specific response from a closed port. This chapter decodes those mechanics.

We deconstruct the **TCP/IP Stack**, analyze the **IPv4/IPv6 headers**, and explain why **Hubs and Switches** handle packet capturing differently—a critical concept for network pivoting.

## 🎯 Who Is This Chapter For?
*   **The Aspiring Penetration Tester:** Who knows how to run Nmap but doesn't understand *why* a SYN scan is stealthier than a Connect scan.
*   **The Network Administrator:** Who wants to understand how their infrastructure (switches, VLANs, DMZs) looks through the eyes of an attacker.
*   **The CPSA Candidate:** Who needs to master **Appendix B (Technical Skills)**, particularly the deep mechanics of TCP/IP, which are heavily weighted in the multiple-choice exam.

## 📝 Learning Objectives
By the end of this chapter, you will be able to:
1.  **Deconstruct the TCP/IP Stack:** Map protocols like TCP, UDP, and ICMP to their correct layers and explain their specific security implications (Skill B1).
2.  **Analyze Network Architecture:** Differentiate between Hubs, Switches, and Routers, and explain how **Collision Domains** and **Broadcast Domains** impact packet capturing (Skill B2).
3.  **Interpret Packet Headers:** Identify key fields in IPv4 and TCP headers (such as TTL, Window Size, and Flags) and explain how attackers manipulate them for evasion.
4.  **Master the 3-Way Handshake:** Describe the exact sequence of flags (SYN, SYN-ACK, ACK) and how deviations (like SYN Floods) create denial-of-service conditions.
5.  **Identify Addressing Schemes:** Recognize Class A, B, and C networks, CIDR notation, and the reserved **RFC 1918** private ranges used in internal networks.
6.  **Explain Network Segmentation:** articulate the security function of VLANs, DMZs, and NACLs in reducing the attack surface.

## 🗺️ CPSA Syllabus Mapping
This chapter covers the following specific skills from the **CREST CPSA Technical Syllabus (v2.5)**:

| Skill ID | Skill Name | Coverage | CPSA Exam Relevance |
| :--- | :--- | :--- | :--- |
| **B1** | IP Protocols | ✅ Comprehensive | **High** - Frequent MCQs on TCP Flags, Headers & Handshakes |
| **B2** | Network Architectures | ✅ Comprehensive | **Medium** - Focus on VLANs, DMZs, and physical media |

## 🛠️ Key Concepts Covered
*   **The OSI vs. TCP/IP Models:** Where security controls live.
*   **Collision vs. Broadcast Domains:** Why you can't sniff a switched network without SPAN/Mirroring.
*   **The TCP 3-Way Handshake:** SYN, SYN-ACK, ACK (and how to break it).
*   **TCP Flags:** SYN, FIN, RST, PSH, URG, ACK.
*   **IPv4 Addressing:** Classes, CIDR, and RFC 1918 Private Ranges.
*   **IPv6 Fundamentals:** Structure, Link-Local (FE80::), and Multicast.
*   **Network Segmentation:** VLANs (802.1Q) and DMZ Design.

## 📚 Recommended Reading
To deepen your understanding of these core topics, the following resources are recommended:
*   *Network Security Assessment (3rd Edition)* – Chris McNab (Chapter 2: IP Protocols)
*   *Nmap Network Scanning* – Gordon Lyon (Chapter 5: Port Scanning Techniques)
*   *TCP/IP Illustrated, Vol 1* – W. Richard Stevens (For deep header analysis)

---
*This chapter is part of the open-source **CREST CPSA Study Guide**. Contributions, corrections, and pull requests are welcome!*
