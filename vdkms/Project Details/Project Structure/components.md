---
title: Components
has_children: false
layout: default
parent: Project Structure
grand_parent: Project Details
nav_order: 2
permalink: /project-details/structure/components
---

# Components

The `components/` folder contains all the React components used across the application. These components are divided into subfolders based on their functionality, ensuring modularity and ease of maintenance.

---

- `animated/`: This subfolder contains animated components used to display loading indicators or transition effects in the UI.

```plaintext
components/animated/
    ├── ButtonLoading.tsx             # Displays a loading animation for buttons
    ├── ConnectionLoading.tsx         # Loading animation for connection establishment
    ├── CredentialAdded.tsx           # Animation indicating a credential has been added
    ├── CredentialPending.tsx         # Shows pending state with animation for a credential
    ├── LoadingIndicator.tsx          # General loading spinner
    ├── RecordLoading.tsx             # Animation for loading record data
    ├── SendingProof.tsx              # Animation for sending proof process
    └── SentProof.tsx                 # Animation indicating proof has been sent
```

---

- `buttons/`: This folder holds various button components used for navigation and action handling throughout the app.

```plaintext
components/buttons/
    ├── Button.tsx                    # Generic button for reusable actions
    ├── HeaderButton.tsx              # Button displayed in the header section
    ├── HeaderHome.tsx                # Home button in the header
    ├── index.ts                      # Entry point for button exports
    ├── InfoIcon.tsx                  # Information icon button
    └── SettingsMenu.tsx              # Button for accessing the settings menu
```

---

- `chat/`: Components related to chat features, including message bubbles and input fields.

```plaintext
components/chat/
    ├── ActionSlider.tsx              # Slider for choosing actions in chat
    ├── ChatActions.tsx               # Displays available chat actions
    ├── ChatBubble.tsx                # Single chat message bubble
    ├── ChatEvent.tsx                 # Handles chat-related events
    ├── ChatMessage.tsx               # Represents a chat message structure
    ├── index.ts                      # Entry point for chat components
    └── MessageInput.tsx              # Input field for typing messages
```

---

- `inputs/`: Input components that handle various types of data input, such as checkboxes, text fields, and PIN input fields.

```plaintext
components/inputs/
    ├── CheckBoxRow.tsx               # Checkbox input in a row layout
    ├── LimitedTextInput.tsx          # Text input with character limit
    ├── PINInput.tsx                  # Input field for entering a PIN code
    └── SingleSelectBlock.tsx         # Single-select input block
```

---

- `listItems/`: Components for displaying items in a list format, such as contacts and notifications.

```plaintext
components/listItems/
    ├── ContactListItem.tsx           # Represents a contact in a list
    └── NotificationListItem.tsx      # Represents a notification in a list
```

---

- `misc/`: Contains miscellaneous components that don’t fit into specific categories but are important for various functionalities in the app.

```plaintext
components/misc/
    ├── ActivityLogLink.tsx           # Link to activity log
    ├── AvatarView.tsx                # Displays user avatars
    ├── BLEScanner.tsx                # Bluetooth Low Energy (BLE) scanner
    ├── CardWatermark.tsx             # Watermark for credential cards
    ├── ConnectionAlert.tsx           # Alert for connection issues
    ├── ConnectionImage.tsx           # Displays images related to connections
    ├── ContentGradient.tsx           # Gradient effect for content views
    ├── CredentialCard.tsx            # Credential details in card format
    ├── EmptyList.tsx                 # Display for empty lists
    ├── Pagination.tsx                # Pagination component for lists
    ├── QRRenderer.tsx                # Renders QR codes
    └── QRScanner.tsx                 # QR code scanner
```

---

- `modals/`: Modal components used to display pop-ups and alerts across the application.

```plaintext
components/modals/
    ├── AlertModal.tsx                # Modal for displaying alerts
    ├── CommonRemoveModal.tsx         # Modal for removal confirmations
    ├── ErrorModal.tsx                # Displays error messages in a modal
    ├── ImageModal.tsx                # Modal for viewing images
    └── PopupModal.tsx                # Generic popup modal
```

---

- `network/`: Components related to network status and connectivity information.

```plaintext
components/network/
    └── NetInfo.tsx                   # Displays network information and connectivity status
```

---

- `record/`: Components that manage and display data records, including fields and headers.

```plaintext
components/record/
    ├── Record.tsx                    # Main record display component
    ├── RecordBinaryField.tsx         # Displays binary fields in a record
    ├── RecordFooter.tsx              # Footer component for records
    ├── RecordHeader.tsx              # Header component for records
    └── RecordRemove.tsx              # Component to remove a record
```

---

- `texts/`: Text and label components used for displaying different types of text across the app.

```plaintext
components/texts/
    ├── HeaderTitle.tsx               # Header title text
    ├── HighlightTextBox.tsx          # Text box with highlighted content
    ├── Label.tsx                     # Generic label component
    ├── Link.tsx                      # Clickable link component
    └── Title.tsx                     # Title text component
```

---

- `toast/`: Toast notification components that display transient messages.

```plaintext
components/toast/
    ├── BaseToast.tsx                 # Base toast component
    └── ToastConfig.tsx               # Toast configuration
```

---

- `tour/`: Components related to the tour or step-by-step walkthroughs in the app.

```plaintext
components/tour/
    ├── CredentialOfferTourSteps.tsx  # Steps for offering credentials during tour
    ├── HomeTourSteps.tsx             # Steps for home screen tour
    ├── SpotCutout.tsx                # Highlights specific elements during tour
    └── TourOverlay.tsx               # Overlay for tour walkthrough
```

---

- `views/`: Contains components related to layout sections of the app, such as headers and footers.

```plaintext
components/views/
    ├── HomeFooterView.tsx            # Footer view for the home screen
    ├── HomeHeaderView.tsx            # Header view for the home screen
    ├── LoadingView.tsx               # Loading screen view
    └── SafeAreaScrollView.tsx        # Scroll view with safe area support
```

---

This structure provides a clear and organized overview of the `components/` folder. Each subfolder serves a specific purpose, contributing to the modularity and maintainability of the application.
