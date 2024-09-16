---
title: Hooks
has_children: false
layout: default
parent: Project Structure
grand_parent: Project Details
nav_order: 5
permalink: /project-details/structure/hooks
---

# Hooks

The `hooks/` folder contains custom React hooks designed to abstract and reuse stateful logic across components. These hooks help manage different application functionalities, such as connections, credentials, and notifications.

---

```plaintext
hooks/
    ├── connections.ts               # Manages connection-related logic in the app
    ├── credentials.ts               # Handles logic related to managing credentials
    ├── deep-links.ts                # Manages deep link navigation and logic
    ├── notifications.ts             # Handles notification logic across the app
    ├── proof-request-templates.ts   # Manages templates for proof requests
    └── proofs.ts                    # Manages proof-related logic and processes
```
