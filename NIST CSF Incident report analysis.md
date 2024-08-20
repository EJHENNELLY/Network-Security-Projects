**Incident report analysis**

**Instructions**

As you continue through this course, you may use this template to record your findings after completing an activity or to take notes on what you've learned about a specific tool or concept. You can also use this chart as a way to practice applying the NIST framework to different situations you encounter.

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

