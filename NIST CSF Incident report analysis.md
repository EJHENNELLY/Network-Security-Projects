# Cybersecurity Framework NIST  

> Please visit this [link](https://www.coursera.org/learn/networks-and-network-security?specialization=google-cybersecurity) for further information.

## Scenario 

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 
The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 
To address this security event, the network security team implemented: 
A new firewall rule to limit the rate of incoming ICMP packets
Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
Network monitoring software to detect abnormal traffic patterns
An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics
As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity incident and integrate your analysis into a general security strategy:

1. Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 
2. Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 
3. Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 
4. Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 
5. Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.

| Summary | The organization experienced a DDoS attack which took the internal network offline for 2 hours. The network received a sudden flood of ICMP packets to the server. Normal traffic was unable to access the network which caused the incident management team to respond by blocking all incoming ICMP packets and then taking all non-critical network services offline before restoring the critical services.  The cybersecurity team conducted their investigation and found that a multiple malicious IP addresses sent a flood of ICMP pings into the network through an unconfigured firewall. Because the attack came from multiple IPs, we have concluded that this was a distributed denial-of-service attack brought on by malicious actors. The organizations network was shut down for 2 hours. In response the security team implemented a new firewall rule to limit the rate of incoming ICMP packets as well as source IP address verification to check for spoofed IP addresses on incoming ICMP packets. They also installed a network monitoring software to detect abnormal traffic patterns. A new IDS/IPS system was also implemented to filter out some ICMP traffic based on similar characteristics. |  |  |
| :---- | :---- | ----- | ----- |
| Identify | The organizations website server was flooded with ICMP packets from multiple malicious actors at the same time. Because of the differing IPs we can conclude that this was a distributed denial of service flood attack.  |  |  |
| Protect | The cybersecurity team implemented a new firewall rule to reduce the amount of ICMP packets to the server. They also installed an IDS/IPS system to filter out similar suspicious ICMP traffic. |  |  |
| Detect | The team implemented a IP verification on the firewall to check for IP spoofing on incoming packets. |  |  |
| Respond | In the future, the team should use network segmentation to isolate affected systems and prevent disruption to the entire network. They can then take the effected systems offline and recover the critical systems that were attacked. The team will implement new monitoring rules to check for malicious activity. |  |  |
| Recover | Once the network is restored to it’s full functioning state, the security team needs to analyze logs for suspicious and repeated activities to know how they can configure the firewall to block the attacks. |  |  |

---

| Reflections/Notes: |
| :---- |

