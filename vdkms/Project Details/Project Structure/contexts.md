---
title: Contexts
has_children: false
layout: default
parent: Project Structure
grand_parent: Project Details
nav_order: 4
permalink: /project-details/structure/contexts
---

# Contexts

The `contexts/` folder contains files that handle the global state management of the application using React's Context API. It provides a centralized way to manage various application states such as authentication, network, configuration, and theme.

---

```plaintext
contexts/
    ├── animated-components.ts        # Manages the state of animated components across the app
    ├── auth.tsx                      # Handles authentication context for managing user login state
    ├── commons.tsx                   # Common context shared across multiple components
    ├── configuration.tsx             # Stores global configuration data accessible throughout the app
    ├── index.ts                      # Main entry point for exporting all context files
    ├── network.tsx                   # Handles the network state, including connectivity status
    ├── store.tsx                     # Context for managing application-level store and state
    ├── theme.ts                      # Manages theme state for handling dark/light modes and other theme settings
    ├── reducers/                     # Folder for reducers, which handle state updates
    │   ├── index.ts                  # Combines all reducers for managing state changes
    │   └── store.ts                  # Reducer handling updates to the global store
    └── tour/                         # Folder for managing tour-related contexts
        ├── tour-context.tsx          # Manages state for the application's tour steps
        └── tour-provider.tsx         # Provides the context for managing the tour state
```

### Breakdown of Key Files and Subfolders:

1. **animated-components.ts**: Manages the state of animated components across the app, such as loading indicators or transitions.
2. **auth.tsx**: Responsible for managing authentication states, including user login and session handling.
3. **commons.tsx**: Provides shared context that can be used across multiple components, facilitating common state management.
4. **configuration.tsx**: Stores and manages the global configuration settings, making them accessible throughout the application.
5. **index.ts**: The main entry point for exporting all context-related files, allowing them to be easily imported elsewhere in the app.
6. **network.tsx**: Tracks the network status, such as online/offline state and network connectivity issues.
7. **store.tsx**: Manages the global state of the application, acting as a centralized store for all state data.
8. **theme.ts**: Responsible for managing the theme (dark/light mode) of the application, enabling a consistent look and feel across components.

---

### Reducers Folder

- **reducers/index.ts**: Combines all the reducers, which are responsible for handling changes to the global state.
- **reducers/store.ts**: A specific reducer that updates the application's global store based on actions dispatched by components.

---

### Tour Context Folder

- **tour/tour-context.tsx**: Manages the state related to the application's tour, including the steps a user needs to follow.
- **tour/tour-provider.tsx**: Provides the context for managing and updating the tour state across different components.

---

This structure ensures that global state management is centralized and accessible across the entire application, allowing for a more maintainable and scalable solution.
