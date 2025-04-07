# Tactical RMM Agent Manager - User Guide

> **Disclaimer:** This app is an independent project and is not made by or affiliated with Tactical RMM/AmidaWare.

> **Note:** You must have your own Tactical RMM Server.

---

## Table of Contents
1. [Overview](#overview)
2. [Installation](#installation)
3. [Configuration](#configuration)
   - [How to Get Your API Key](#how-to-get-your-api-key)
4. [Using the App](#using-the-app)
   - [API Settings](#api-settings)
   - [Agent Management](#agent-management)
   - [Agent Actions](#agent-actions)
5. [First Run Guide Pop-Up](#first-run-guide-pop-up)
6. [Open Source](#open-source)
7. [Support](#support)

---

## Overview

Tactical RMM Agent Manager is built with SwiftUI and is designed to monitor and control agents on your Tactical RMM Server using the API endpoint. 

> **Note:** This app is not made by Tactical RMM. It is a third-party solution that integrates with Tactical RMM's API.

---

## Installation

The app is available on the **Apple App Store**. To install:

1. Open the App Store on your device.
2. Search for **"Independent Agent Manager"**.
3. Tap **Download** and install the app.

---

## Configuration

Before using the app, you need to set up your API configuration.

### API Settings

1. Launch the app.
2. Enter your **API URL** (the base URL for your API) in the "API URL" field.
3. Enter your **API Key** in the "API Key" field.
4. If your settings match the saved configuration, tap **Login**.  
   Otherwise, tap **Save & Login** to update the settings and fetch agents.

### How to Get Your API Key

To generate or retrieve your API key, refer to the official Tactical RMM documentation:

[How to Get API Key](https://docs.tacticalrmm.com/functions/api/#api-access)

Follow the steps outlined in the documentation to obtain your API key.

---

## Using the App

### Agent Management

- **Agents List**: After logging in, you will see a list of agents displaying:
  - Hostname
  - Operating System
  - CPU Model
  - Public IP (if available)
  - Status (with green indicating online and red indicating offline)

- **Agent Details**: Tap an agent to view detailed information and additional options.

### Agent Actions

Within an agent’s detail view, you have four buttons for remote actions:

- **Shutdown**: Sends a command to shut down the agent.
- **Reboot**: Sends a command to reboot the agent.
- **Control**: Opens a console session or control interface for direct interaction with the agent using MeshCentral.
- **Take Control**: Connects to the agent’s control URL for full remote control using MeshCentral.

*Note*: The functionality of "Control" versus "Take Control" may vary depending on your configuration and the agent's operating system.

---

## First Run Guide Pop-Up

On the first launch, the app displays a pop-up with the following message:

> "Seems like you're new here, we recommend reading the guide."

You have two options:
- **Read Guide**: Opens your web browser to the detailed guide page.
- **Disregard**: Closes the pop-up so you can start using the app immediately.

This feature helps first-time users to set up the app.

---
## Open Source

You can find the source code [here](https://github.com/Jerdal-F/TRMM-Manager)


## Support

For questions and support, please open an issue on this GitHub repository.
