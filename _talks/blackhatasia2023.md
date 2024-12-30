---
title: "Dilemma in IoT Access Control: Revealing Novel Attacks and Design Challenges in Mobile-as-a-Gateway IoT"
collection: talks
type: "Talk"
permalink: /talks/blackhatasia2023
venue: "Black Hat (Asia) 2023"
date: 2023-05-11
location: "Sigapore"
---

From Bluetooth smart locks to item trackers, Mobile-as-a-Gateway (MaaG) IoT devices are everywhere. MaaG IoT devices use mobile devices as gateways to connect to the internet for management. They allow for remote access sharing and revocation, while also providing "offline availability" for enhanced usability. However, in order for these functionalities to be realized, secure cooperation among the cloud service, the companion app, and the IoT device is necessary. In practice, it is common for cloud services to use access model translation (AMT) to convert complex cloud-side access policies into simpler device-side policies. At the same time, ad-hoc protocols are often developed to support access policy synchronization, using both HTTPS and Bluetooth. Unfortunately, current MaaG IoT systems fail to recognize the potential security risks associated with this process of access model translation and synchronization. An analysis of ten top-of-the-line MaaG IoT devices revealed that all of them have significant vulnerabilities, such as allowing irrevocable and permanent access for temporary users. Finally, we will propose a secure protocol design to defend against all identified attacks. [link](https://www.blackhat.com/asia-23/briefings/schedule/index.html#when-https-meets-bluetooth-unpatchable-cross-protocol-design-flaws-for-mobile-as-a-gateway-iot-devices-31040)



