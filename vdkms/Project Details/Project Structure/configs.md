---
title: Configs
has_children: false
layout: default
parent: Project Structure
grand_parent: Project Details
nav_order: 3
permalink: /project-details/structure/configs
---

# Configs

The `configs/` folder contains the configuration files necessary for managing different parts of the application's setup, particularly focused on ledger management and testing.

---

- `ledgers/`: This subfolder holds configurations related to ledger management. In this case, it specifically focuses on `indy` ledger technology. It also includes mock data used for testing purposes.

```plaintext
configs/ledgers/
    └── indy/
        ├── index.ts                   # Main index file for the Indy ledger configuration
        ├── ledgers.json               # JSON file containing ledger configurations
        └── __mocks__/                 # Contains mock data used for testing
            ├── index.ts               # Mock index file for testing purposes
            └── fixtures/
                └── sovrin-main-net-pool.json  # Mock fixture for the Sovrin main net pool
```
