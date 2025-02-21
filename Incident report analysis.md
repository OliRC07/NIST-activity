**Incident report analysis**

**Instructions**

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

* A new firewall rule to limit the rate of incoming ICMP packets  
* Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets  
* Network monitoring software to detect abnormal traffic patterns  
* An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy.

| Summary | Today, the organization’s network services suddenly stopped responding. Logs showed an incoming flood of ICMP packets from various devices. The incident management team blocked incoming ICMP packets, stopped all non-critical network services offline, and restored critical network services. The investigation by the cybersecurity team showed a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall, which vulnerability allowed him to overwhelm the company’s network through a distributed denial of service (DDoS) attack. |  |  |
| :---- | :---- | ----- | ----- |
| Identify | A malicious actor attacked the company’s network with an ICMP flood. The internal network was compromised for two hours, and the clients were not able to access network resources and services, which needed to be secured and restored.  |  |  |
| Protect | The client needed access to the affected network. To stop the malicious actor from having access to it, the Incident Management team blocked all incoming ICMP packets. Network legitimate users needed to be aware of this attack because it could impact their work and business. In order to prevent this event from happening again, the cybersecurity team implemented a new firewall rule to control the rate of incoming ICMP packets and used an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.  |  |  |
| Detect | The cybersecurity team implemented a source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets, and also implemented network monitoring software to detect abnormal traffic patterns.  |  |  |
| Respond | If such an event happens again in the future, the security team should first isolate the system concerned in order to prevent the entire system from being affected. The next step will be to secure and restore the system affected. Afterwards, the team will have to check SIEM tools to analyze the logs and identify any abnormal activity. Finally, the incident should be documented, the organization’s leadership should be informed and we should apply this new framework.  |  |  |
| Recover | Access to network services must be restored under normal operating conditions A network security hardening should be performed. Firewall rules should regularly be maintained in order to block ICMP flooding. The priority is to restore critical assets and protect them ( patch updates…). Once the incident is resolved, non-critical assets can be restored. |  |  |

