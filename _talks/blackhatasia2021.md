---
title: "How I Can Unlock Your Smart Door: Security Pitfalls in Cross-Vendor IoT Access Control"
collection: talks
type: "Talk"
permalink: /talks/blackhatasia2021
venue: "Black Hat (Asia) 2021"
date: 2021-05-07
location: "Singapore"
---

Internet of Things (IoT) devices are increasingly managed through the clouds, which mediate the users' access to devices, e.g., only authorized users can unlock a door. These clouds are operated by device vendors (Philips Hue, LIFX, Tuya, etc.) or cloud providers (Google Home, Amazon Alexa, IFTTT, etc.). Of particular interest here is the emerging capability, advocated by mainstream IoT vendors, to delegate device access across different clouds and users: for example, Philips Hue, August Lock, etc., allow Google Home to control devices mediated under their clouds, so the user can manage multiple devices from different vendors all through the single console at Google Home. On Google Home, then, an Airbnb host may temporarily delegate the access to their smart lock to a guest during their stay. Such a capability can lead to a convoluted delegation chain, whose authorization operations could easily go wrong. Specifically, access delegation across IoT clouds is distributed, heterogeneous, and unverified: each vendor customizes its delegation protocol with ad-hoc, implicit security assumption; further, we found the complicated delegation service is often coupled across clouds, with one cloud unwittingly violating the other's security operations and assumptions. We report the first systematic study on cross-cloud IoT delegation, based upon a verification tool we developed. We investigated 10 mainstream IoT clouds (Google Home, SmartThings, IFTTT, Philips Hue, LIFX, August, etc.), and discovered 5 serious vulnerabilities that endanger millions of users and hundreds of vendors. Exploiting the vulnerabilities, the adversary (e.g., former employee, Airbnb tenant) can gain unauthorized access to IoT devices (e.g., smart locks, switches, safety sensors). We implemented end-to-end attacks for all vulnerabilities and reported to affected vendors, which have deployed or scheduled fixes. We further propose principles for developing more secure cross-cloud IoT delegation services, before a standardized solution can be widely deployed. <br>[link](https://www.blackhat.com/asia-21/briefings/schedule/index.html#how-i-can-unlock-your-smart-door-security-pitfalls-in-cross-vendor-iot-access-control-21816)



