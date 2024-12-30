---
title: "IoT Manufacturers' New Nightmare: Design Flaws and Deployment Chaos in Cloud-based IoT Access Control Policies"
collection: talks
type: "Talk"
permalink: /talks/blackhateuro2022
venue: "Black Hat (Europe) 2022"
date: 2022-12-07
location: "London, UK"
---

Modern internet-of-things device manufacturers are taking advantage of the managed Platform-as-a-Service (PaaS) and Infrastructure-as-a-Service (IaaS) IoT clouds (e.g., AWS IoT, Azure IoT) for secure and convenient IoT development/deployment. The IoT access control is achieved by manufacturer-specified, cloud-enforced IoT access policies (e.g., cloud-standard JSON documents, called IoT Policies on AWS IoT) stating which users can access what IoT devices/resources under what constraints. However, IoT access control policy is often complicated to develop or deploy securely, with tremendous space for device manufacturers to program a flawed IoT access policy, leading to severe security loopholes for IoT users and IoT manufacturers whose IoT applications/deployments are based on the modern IoT clouds. In this presentation, we'll unearth both design flaws and bad deployment practices of IoT policies by many real manufacturers. We will introduce four new types of flaws (zero-days) that manufacturers often make, generalized as (1) a semantic gap in IoT access policies, (2) flawed cooperation between IAM policy and IoT policy, (3) dilemma with IoT policy templates, and (4) the constraint of IoT-policy mutual exclusion. The first two flaws are from the design space, and the last two are from the deployment/implementation space. Those flaws were found in 36 IoT manufacturers and 310 open-source AWS-IoT-based projects from GitHub (13 of the manufacturers suffer from 25 instances of the new flaws and 172 of the IoT policies from Github are flawed). We reported our findings to affected manufacturers, GitHub project owners, and AWS. Most of the vendors have acknowledged the problems, and AWS is working with us to solve the flaws fundamentally. We will also introduce our new formal verification tool named P-Verifier to help developers and manufacturers with their IoT access policies and avoid these flaws before their production release, and our evaluation shows that P-Verifier is highly usable and accurate. <br>[link](https://www.blackhat.com/eu-22/briefings/schedule/index.html#iot-manufacturers-new-nightmare-design-flaws-and-deployment-chaos-in-cloud-based-iot-access-control-policies-29365)



