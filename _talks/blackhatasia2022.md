---
title: "Codema Attack: Controlling Your Smart Home Through Dangling Management Channels"
collection: talks
type: "Talk"
permalink: /talks/blackhatasia2022
venue: "Black Hat (Asia) 2022"
date: 2022-05-13
location: "Singapore"
---

An IoT device today can be managed through different channels, e.g., by its device manufacturer's app, or third-party channels such as Apple's iOS Home app, or a smart speaker. Supporting each channel is a management framework integrated in the device and provided by different parties. For example, a device that integrates Apple HomeKit framework can be managed by Apple Home app. We call the management framework of this kind, including all its device and cloud-side components, a device management channel (DMC). Four third-party DMCs are widely integrated in today's IoT devices along with the device manufacturer's own DMC: HomeKit, Zigbee/ZWave compatible DMC, and smart-speaker Seamless DMC. Each of these DMCs is a standalone system that has full mandate on the device; however, if their security policies and control are not aligned, consequences can be serious, allowing a malicious user to utilize one dangling DMC to bypass the security control imposed by the device owner on another DMC. We call such a problem Chaotic Device Management (Codema). We analyzed 14 top-rated IoT devices and their integration and management of multiple DMCs. We found that Codema is both general and fundamental: these DMCs are generally not designed to coordinate with each other for security policies and control. The Codema problems enable the adversary to practically gain unauthorized access to sensitive smart home devices (e.g., locks, garage doors, etc.). We reported our findings to affected parties (e.g., Apple, August Home, Philips Hue, ismartgate, Abode), which all acknowledged their importance. To mitigate this new threat, we designed and implemented CGuard, a new access control framework that device manufacturers can easily integrate into their IoT devices to protect end users. Our evaluation shows that CGuard is highly usable and acceptable to users, easy to adopt by manufacturers, and efficient and effective in security control. [link](https://www.blackhat.com/asia-22/briefings/schedule/index.html#codema-attack-controlling-your-smart-home-through-dangling-management-channels-26064)



