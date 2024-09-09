---
title: Multi-use Invitations
layout: default
nav_order: 2
parent: Infrastructure
permalink: /infrastructure/multi-use-invitations
---

# Sending Multi-Use Invitations


### Overview

This section explains how infrastructure creates a new multi-use invitation which when recieved by the vehicle becomes a private dedicated connection to the system.

### Steps to Create an Invitation

1. **Utilizing the Invitation Script**

   - The infrastructure server provides a dedicated Python script to create a multi-use invitation with option to convert the invitation to a QR code for the agent to scan.
   - The script also provides option to share the QR code to a S3 bucket to easily access and share with other vehicles.

2. **Accept the Invitation in FHWA Mobile Application**

   - **Step 1**: The mobile application can scan the infrastructure QR code to connect with it. Once connected the infrastructure will appear as a Infrastructure contact in list of Infrastructures in mobile application.


   ![FHWA Mobile View]({{ site.baseurl }}/assets/images/infrastructure-list.png)

   - **Step 2**: In the list of infrastrucutres select the infrastructure to view its messages and interact with it.


   ![Infrastructure List]({{ site.baseurl }}/assets/images/infrastructure-list2.png)

   - **Step 3**: The contact with open and you can view the messages.

   ![Infrastructure Contact]({{ site.baseurl }}/assets/images/message.png)
   
### Notes

- **Dedicated Connections from Multi-Use Invitations**:
  - The multi-use invitations work on principle of one-to-many connections. One single connection is used to initially connect to the system which then branches into a dedicated single connection to the system.

