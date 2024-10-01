---
title: Navigators
has_children: false
layout: default
parent: Project Structure
grand_parent: Project Details
nav_order: 7
permalink: /project-details/structure/navigators
---

# Navigators

The `navigators/` folder manages the routing and navigation within the application. Each file defines a navigation stack that controls the flow between different screens in the app.

---

```plaintext
navigators/
    ├── AuthenticateStack.tsx         # Stack for handling authentication-related navigation
    ├── ConnectStack.tsx              # Stack for managing connections navigation flow
    ├── ContactStack.tsx              # Stack for navigating between contact-related screens
    ├── CredentialStack.tsx           # Stack for managing credential-related navigation
    ├── defaultStackOptions.tsx       # Default options for configuring all navigation stacks
    ├── DeliveryStack.tsx             # Stack for managing delivery-related screens
    ├── HomeStack.tsx                 # Stack for navigating through the home screens
    ├── NotificationStack.tsx         # Stack for managing notification-related screens
    ├── ProofRequestStack.tsx         # Stack for navigating through proof request screens
    ├── RootStack.tsx                 # Root stack that brings together all the other navigation stacks
    ├── ServiceContactStack.tsx       # Stack for navigating through service contact-related screens
    ├── SettingStack.tsx              # Stack for managing settings-related navigation
    └── TabStack.tsx                  # Stack for managing tab navigation within the app
```
