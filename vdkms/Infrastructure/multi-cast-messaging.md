---
title: MultiCast Messaging
layout: default
nav_order: 3
parent: Infrastructure
permalink: /infrastructure/multicast-messaging
---

# Multicast Messaging

### Prerequisites

Before receiving messages from infrastructure, make sure you have an active connection to the infrastructure. Refer to the [Multi-Use Invitations](multi-use-invitations) instructions.

### Overview

This section explains the messages infrastructure broadcasts to the connected devices and explores two scenarios where the device may receive messages from the infrastructure.

### Messages

**Infrastructure Messages**

   - The system is built upon an infrastructure that utilizes an Aries agent as its core component, and this agent is responsible for broadcasting messages to all connected devices within the network.
   
   - The broadcast messages are primarily based on real-time events and current scenarios in the environment.
   
   - Examples of such events include:
      - Vehicles approaching an intersection
      - Ongoing construction activities on upcoming street segments

   - This infrastructure has the potential to significantly enhance urban mobility and safety through its real-time communication capabilities.

**Multi-cast Script**

   - There is a script in the infrastructure system that is used to broadcast messages to all connected devices.
   - The systems responsible for the messages based on events are connected to the infrastructure and utilize the HTTP REST endpoint to communicate with the infrastructure.
   - The infrastructure, after receiving the messages, sends them to the connected devices in the network by utilizing the script.

### Scenario 1: Vehicle crossing at an intersection


1. **Drone Footage of Vehicle Approaching**

   ![Drone of Vehicle Approaching]({{ site.baseurl }}/assets/images/car_drone.png)

2. **Camera Footage of Vehicle Approaching**

   ![Camera Footage of Vehicle Approaching]({{ site.baseurl }}/assets/images/car_incar.png)

3. **In-Screen Recording of FHWA Application when Vehicle is Approaching**

   ![In-Screen Recording of Vehicle Approaching]({{ site.baseurl }}/assets/images/car_screen.png)

### Scenario 2: Construction happening on site

1. **Server Footage of the System showing Construction**

   ![Server Recording of Construction Event]({{ site.baseurl }}/assets/images/image12.png)

2. **In-Screen Recording of FHWA Application when Construction is Happening**

   ![In-Screen Recording of Construction Event]({{ site.baseurl }}/assets/images/image11.png)
