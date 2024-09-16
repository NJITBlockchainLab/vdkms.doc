---
title: Screens
has_children: false
layout: default
parent: Project Structure
grand_parent: Project Details
nav_order: 8
permalink: /project-details/structure/screens
---

# Screens 

The `screens/` folder contains the React components that represent each screen in the application. Each file encapsulates the layout, interaction, and styling seen by the user on that specific screen.

---

```plaintext
screens/
    ├── AttemptLockout.tsx            # Screen shown when too many failed login attempts occur
    ├── Chat.tsx                      # Chat screen for messaging functionality
    ├── Connection.tsx                # Screen for managing connections
    ├── ContactDetails.tsx            # Screen displaying contact details
    ├── CredentialDetails.tsx         # Screen showing detailed information of a credential
    ├── CredentialOffer.tsx           # Screen for offering a credential
    ├── CredentialOfferAccept.tsx     # Screen for accepting a credential offer
    ├── DataRetention.tsx             # Screen for managing data retention settings
    ├── Developer.tsx                 # Developer screen for accessing developer tools or features
    ├── Home.tsx                      # Home screen of the application
    ├── Language.tsx                  # Screen for selecting the language of the app
    ├── ListContacts.tsx              # Screen for listing all contacts
    ├── ListCredentials.tsx           # Screen displaying a list of all credentials
    ├── ListProofRequests.tsx         # Screen for listing proof requests
    ├── Maps.tsx                      # Screen for displaying maps
    ├── NameWallet.tsx                # Screen for naming the user's wallet
    ├── Notification.tsx              # Screen for managing notifications
    ├── Onboarding.tsx                # Main onboarding screen for new users
    ├── OnboardingPages.tsx           # Pages for the onboarding process
    ├── PINCreate.tsx                 # Screen for creating a PIN
    ├── PINEnter.tsx                  # Screen for entering a PIN
    ├── Preface.tsx                   # Introductory screen or preface for the app
    ├── ProofChangeCredential.tsx     # Screen for changing a credential in the proof flow
    ├── ProofDetails.tsx              # Detailed screen for proofs
    ├── ProofRequest.tsx              # Screen for making a proof request
    ├── ProofRequestAccept.tsx        # Screen for accepting a proof request
    ├── ProofRequestDetails.tsx       # Detailed view of a proof request
    ├── ProofRequesting.tsx           # Screen showing proof requesting progress
    ├── ProofRequestUsageHistory.tsx  # Screen for viewing the usage history of a proof request
    ├── QRCodeGen.tsx                 # Screen for generating QR codes
    ├── RenameContact.tsx             # Screen for renaming a contact
    ├── Scan.tsx                      # Screen for scanning QR codes
    ├── ScanBLE.tsx                   # Screen for scanning Bluetooth Low Energy (BLE) devices
    ├── ScanHelp.tsx                  # Help screen for scanning-related issues
    ├── SelectProofRequest.tsx        # Screen for selecting a proof request
    ├── Settings.tsx                  # Screen for managing app settings
    ├── Splash.tsx                    # Splash screen shown when the app is launching
    ├── Terms.tsx                     # Screen displaying terms and conditions
    ├── Tours.tsx                     # Screen for managing app tours or walkthroughs
    ├── UseBiometry.tsx               # Screen for enabling or disabling biometric authentication
    └── WhatAreContacts.tsx           # Informational screen explaining what contacts are
```
