---
title: Localization
has_children: false
layout: default
parent: Project Structure
grand_parent: Project Details
nav_order: 6
permalink: /project-details/structure/localization
---

# Localization

The `localization/` folder manages the language resources for internationalizing the application. This structure supports multiple languages, making the app accessible to a wider audience.

---

```plaintext
localization/
    ├── index.ts                     # Main index file for exporting language configurations
    ├── en/                          # Folder containing English translations
    │   └── index.ts                 # English translation file
    ├── fr/                          # Folder containing French translations
    │   └── index.ts                 # French translation file
    └── pt-br/                       # Folder containing Brazilian Portuguese translations
        └── index.ts                 # Brazilian Portuguese translation file
```
