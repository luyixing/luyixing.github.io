---
title: "Design Pitfalls in Commercial Mini-Programs on Android and iOS"
collection: talks
type: "Talk"
permalink: /talks/blackhateuro2020
venue: "Black Hat (Europe) 2020"
date: 2020-12-09
location: "London, UK"
---

A new, commercial mobile-computing paradigm, dubbed app-in-app, is gaining high popularity in the past years. Under the paradigm, a mobile app, called host app or host, operates a set of sub-apps (a.k.a. mini-programs) as its in-app components. These mini-programs give users native app like experience and enriched functionalities (e-commerce, banking, health, travel management, food delivery, etc.), thereby increasing their "stickiness" to the host: one does not need to leave the app if it does everything. Mini-programs are installed by the users from the host's mini-program store, just like Google Play and Apple app store, which fosters an ecosystem around the host app. Wechat, for example, a host with one billion users, has one million mini-programs in its store and 200 million daily mini-program users. Nowadays, this app-in-app paradigm has been hosted by many popular apps such as Wechat, Alipay, TikTok, Baidu, etc., with other app vendors (e.g., Amazon, Google, Microsoft, Samsung, Airbnb, HSBC) actively releasing mini-programs to these hosts. Mini-programs access system resources (e.g., camera, microphone, location, contacts) through the mediation of the hosts, which developed access control to manage mini-programs, similar to how the OS manages apps. Less clear, however, is whether the host, a third-party app without OS-level privilege, is capable of securely managing system resources and mini-programs. In this research, we show the first systematic security analysis on 11 popular commercial app-in-app ecosystems. We found four new, serious vulnerabilities, which allow the adversary (zero-permission mini-program) to stealthily escalate his privilege (e.g. accessing the camera, photo gallery, microphone, etc.) or acquire sensitive data (e.g. location, passwords of Amazon, Google, etc.). The problems affect all 11 hosts on both Android and iOS, with more than 2.6 billion users. We further discuss the lessons learned and possible mitigation strategies. <br>[link](https://www.blackhat.com/eu-20/briefings/schedule/#design-pitfalls-in-commercial-mini-programs-on-android-and-ios-21460)



