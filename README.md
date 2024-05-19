# 🕵️‍♂️ Analyzing Wireless Access Points

## 🛠️ Objective
In this lab I will be analyzing Wireless networks and gather detailed information about specific SSIDs, using `netsh` and `inSSIDer` tools to differentiate between legitimate and rogue access points.

---

## 🎓 Skills Learned
- **Network Analysis**: Identifying and analyzing wireless access points.
- **Command Line Proficiency**: Utilizing `netsh` for network examination.
- **Tool Utilization**: Operating inSSIDer for comprehensive Wi-Fi analysis.
- **Troubleshooting**: Resolving common issues with network analysis tools.
- **Security Awareness**: Understanding the risks associated with rogue access points.

---

## 🔧 Tools Used
- **netsh**: Built-in Windows command-line utility for network configuration.
- **inSSIDer**: Wireless network scanner application for Wi-Fi analysis.

---

## 📋 Steps

<p align="center">
 <br/>
 <img src="https://i.imgur.com/lUkoG4P.png" height="80%" width="80%"/>
 <br />
 <strong>Figure1: Insider has been Installed</strong>
 <br />
 <br />
 <br />
 <img src="https://i.imgur.com/F1rcXMV.png" height="80%" width="80%" alt="Analyzing Wireless Access Points"/>
 <br />
 <strong>Figure2: Using netsh to investigate the network type, Authentication Type security, channels and BSSID:</strong>
 <br />
 <br />
 <br />
 <img src="https://i.imgur.com/QbBuiEx.png" height="80%" width="80%" alt="Analyzing Wireless Access Points"/>
 <br />
 <strong>Figure3: CCSecure can be a possible rogue IP:</strong>
 <br />
 <br />
 <br />
 <img src="https://i.imgur.com/vB6dQ00.png" height="80%" width="80%" alt="Analyzing Wireless Access Points"/>
 <br />
 <strong>Figure4: Using inSSIDer to further investigate:</strong>
 <br />
 <br />
 <br />
  <img src="https://i.imgur.com/F6VtWmS.png" height="80%" width="80%" alt="Analyzing Wireless Access Points"/>
 <br />
 <strong>Figure5: InSSIDer reveals crucial information about the type of access point, which can be used to craft exploits based on known vulnerabilities:</strong>
 <br />
 <br />
</p>

## Reflection
1)	Attackers can create rogue APs because there are no restrictions while naming the SSID, and this technique always works because our device is always looking to connect to the same networks when around the range; this can cause our device to connect to the hackers' network.

2)	It is a major issue once we connect to a hacker's network. He has full control over what goes and comes inside the network, which can result in the loss of Personal Identifiable Information (PII) and even financial login information. The hacker who places himself between the user and the network can launch a man-in-the-middle attack to intercept the traffic and inject a malicious payload.

