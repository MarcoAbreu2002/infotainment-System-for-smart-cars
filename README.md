# Smart Vehicle Infotainment System

Prototype of an infotainment system for intelligent vehicles, featuring voice-controlled interactions such as GPS navigation, user management, and phone calls.

## Overview

This project implements a responsive infotainment prototype that runs locally and is controlled through predefined voice commands. The system is designed to simulate common in-vehicle functionalities, focusing on usability and interaction.

## Setup Instructions

### 1. Screen Resolution
For optimal visualization, set your screen scaling to **100%**.
- On your computer, search for **“Change display resolution”**
- Adjust the scale to **100%** if it is not already set

### 2. Install Dependencies
Before running the project, install the required dependencies:
```bash
npm install
````

### 3. Run the Application

To start the prototype, run:

```bash
node server.js
```

## Voice Commands

The system responds to the following voice commands:

### GPS Navigation

* **Start GPS route**
  Say:

  ```
  GPS start
  ```

  The system will then ask for the destination and route type.

* **Finish GPS route**
  Say:

  ```
  GPS finish
  ```

### User Management

* **Connect a user** (example: James)

  ```
  Connect James
  ```

* **Disconnect a user** (example: James)

  ```
  Disconnect James
  ```

### Phone Calls

* **Start a call** (example: Amy)

  ```
  Call Amy
  ```

## Notes

* Ensure your microphone is properly configured and accessible.
* Voice recognition accuracy may depend on ambient noise and pronunciation.
* The application is intended for demonstration and prototyping purposes.

## Technologies

* Node.js
* JavaScript
* Voice command processing (speech recognition)
