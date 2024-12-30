---
title: "Discovering and Exploiting Novel Security Vulnerabilities in Apple ZeroConf"
collection: talks
type: "Talk"
permalink: /talks/blackhatUSA2016
venue: "Black Hat (USA) 2016"
date: 2016-08-04
location: "Las Vegas, NV"
---

With the proliferation of portable computing systems such as tablet, smartphone, Internet of Things (IoT), etc., ordinary users are facing the increasing burden to properly configure those devices, enabling them to work together. In response to this utility challenge, major device manufacturers and software vendors (e.g., Apple, Microsoft, Hewlett-Packard) tend to build their systems in a "plug-and-play" fashion, using techniques dubbed zero-configuration (ZeroConf). Such ZeroConf services are characterized by automatic IP selection, host name resolving and target service discovery. As the major proponent of ZeroConf techniques, Apple has adopted ZeroConf techniques in various frameworks and system services on iOS and OS X to minimize user involvements in system setup. However, when the design pendulum swings towards usability, concerns may arise whether the system has been adequately protected. In this presentation, we will report the first systematic study on the security implications of these ZeroConf techniques on Apple systems. Our research brings to light a disturbing lack of security consideration in these systems' designs: major ZeroConf frameworks on the Apple platforms, including the Multipeer Connectivity and Bonjour, are mostly unprotected and system services, such as printer discovery and AirDrop, turn out to be completely vulnerable to an impersonation or Man-in-the-Middle (MitM) attack, even though attempts have been made to protect them against such threats. The consequences are serious, allowing a malicious device to steal documents to be printed out by other devices or files transferred between other devices. Most importantly, our study highlights the fundamental security challenges underlying ZeroConf techniques. Some of the vulnerabilities have not been fixed until this submission though we reported to Apple over half a year ago. We will introduce ZeroConf techniques and publish technical details of our attacks to Apple ZeroConf techniques. We will take Airdrop, Bonjour and Multipeer Connectivity as examples to show the vulnerabilities in their design and implementation and how we hacked these ZeroConf frameworks and system services to perform MitM attacks. We will also show that some of vulnerabilities are due to TLS' incompetence to secure device-to-device communication in the ZeroConf scenario, which is novel discovery and contributes to the state of the art. <br>
[link](https://www.blackhat.com/us-16/briefings/schedule/#discovering-and-exploiting-novel-security-vulnerabilities-in-apple-zeroconf-3219)



