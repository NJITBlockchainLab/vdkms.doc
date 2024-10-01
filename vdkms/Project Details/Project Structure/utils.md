---
title: Utils
has_children: false
layout: default
parent: Project Structure
grand_parent: Project Details
nav_order: 11
permalink: /project-details/structure/utils
---

# Utils

The `utils/` folder contains utility functions and helpers that provide widely used functionalities throughout the application. These utilities help in data processing, performing calculations, handling cryptography, and other tasks that are not directly tied to the UI.

---

```plaintext
utils/
    ├── agent.ts                      # Utility functions for managing agents in the app
    ├── cred-def.ts                   # Utilities related to credential definitions
    ├── credential.ts                 # Functions for handling credentials
    ├── crypto.ts                     # Cryptographic functions for encryption and decryption
    ├── helpers.ts                    # General helper functions used across the app
    ├── invitation.ts                 # Utilities for handling invitation creation and management
    ├── ledger.tsx                    # Functions for interacting with the ledger
    ├── luminance.ts                  # Utility for managing luminance and color-related operations
    ├── migration.ts                  # Functions to handle data migrations
    ├── oca.ts                        # Utilities for Open Credential Architecture (OCA) management
    ├── PINCreationValidation.ts      # Utility for validating PIN creation and management
    ├── proofBundle.ts                # Functions for handling proof bundles
    ├── schema.ts                     # Utility for handling schemas within the app
    └── testable.ts                   # Testable utility functions for development and debugging
```
