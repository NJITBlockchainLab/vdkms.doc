---
title: Project Dependencies
has_children: false
layout: default
parent: Project Details
nav_order: 2
permalink: /project-details/dependencies
---

# Project Dependencies

This project leverages a wide array of packages, essential for its functionality in decentralized identity management and mobile app development using React Native. Below are some key dependencies and their purposes:

## Identity and Credential Management

- **@aries-framework/anoncreds**: This package is crucial for managing anonymous credentials within the Aries framework. It supports privacy-preserving credential issuance and verification in self-sovereign identity systems.
- **@aries-framework/core**: The core library of the Aries Framework provides the fundamental building blocks for developing decentralized identity applications, including identity creation, management, and verification.
- **@hyperledger/aries-askar-react-native**: Integrates secure storage and encryption capabilities in React Native for managing secure data queries within decentralized identity systems.
- **@hyperledger/indy-vdr-react-native**: Provides support for ledger transactions in React Native apps, interacting with Hyperledger Indy-based distributed ledgers.

## Mobile App Framework

- **react-native**: The core framework for building mobile applications using JavaScript and React, enabling cross-platform development for iOS and Android.
- **@react-native-async-storage/async-storage**: A local key-value storage system for persisting small amounts of data on the user's device asynchronously.
- **@react-navigation/native, @react-navigation/bottom-tabs, @react-navigation/stack**: A set of libraries used for handling navigation within the React Native app, including stack navigation and tabbed interfaces for a smooth user experience.

## Networking and Permissions

- **axios**: A promise-based HTTP client for making API requests, widely used for data fetching and external service communication in modern applications.
- **react-native-permissions**: Simplifies the management of permissions in iOS and Android, providing a unified API to request and handle app permissions.
- **@react-native-community/netinfo**: Provides real-time network connectivity status, essential for apps that rely on network availability.

## Additional Functionalities

- **react-native-ble-manager**: A package for managing Bluetooth Low Energy (BLE) devices in the mobile app, facilitating communication with hardware devices over BLE.
- **react-native-keychain**: Securely stores credentials and sensitive information in the device’s keychain, improving app security.
