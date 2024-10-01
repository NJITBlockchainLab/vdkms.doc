---
title: Project Structure
has_children: true
layout: default
parent: Project Details
nav_order: 1
permalink: /project-details/structure
---

# Project Structure Overview

All the application's source files, assets, and components are in the `App` folder, which can be found within the `packages\legacy\core\App` directory from the root folder.

```plaintext
packages/legacy/core/App/
  ├─ assets/                   # Contains static resources like images, fonts, and stylesheets
  ├─ components/               # Organized UI components, divided into subdirectories based on functionality
  ├─ configs/                  # Centralized configuration settings
  ├─ contexts/                 # Global state management using React's Context API to simplify data flow
  ├─ hooks/                    # Custom React hooks to abstract and reuse stateful logic across components
  ├─ localization/             # Language resources for internationalization, supporting multiple languages
  ├─ navigators/               # Manages routing/navigation for screen flow
  ├─ screens/                  # React components representing screens
  ├─ services/                 # Service functionalities (secure storage, centralized logging)
  ├─ types/                    # TypeScript types for data structure consistency and type checking
  ├─ utils/                    # Utility functions for common tasks and data processing
  ├─ animated-components.ts    # Animated components to be reused throughout the application
  ├─ constants.ts              # Stores constant values used across the application
  ├─ defaultConfiguration.ts   # Default configurations and setup for the app
  ├─ index.ts                  # Main entry point for exporting all components, utilities, and services
  └─ theme.ts                  # Application-wide theme settings and styles
```
