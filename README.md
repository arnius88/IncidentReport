<h1>Incident report with NIST CSF </h1>

<h2>Description</h2>

The project consists of analyzing a network incident following the the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF).<br />

The [**NIST CSF**](https://www.nist.gov/cyberframework)is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. The CSF is scalable and can be applied in a wide variety of contexts.<br />

I applied the five functions of the  NIST CSF and produced an [_incident report_](https://github.com/arnius88/IncidentReport/blob/main/Incident%20report%20analysis.pdf), where I covered:<br />

- identify the type of attack and the systems affected
- how to protect the assets in your organization from being compromised
- determine how to detect similar incidents in the future
- create a response plan for future cybersecurity incidents
- help the organization recover from the incident
<br />



<h2>Scenario</h2>

>You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

>During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

>The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 
To address this security event, the network security team implemented: 
•	A new firewall rule to limit the rate of incoming ICMP packets
•	Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
•	Network monitoring software to detect abnormal traffic patterns
•	An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

>As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate. 

<h2>Learnings </h2>




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
