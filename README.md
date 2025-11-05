# SanchiAR - AR QR Code Application

## 1\. Project Overview
**Stupa** is an augmented reality (AR) application designed to demonstrate real-time object placement by scanning a QR code. Users can scan a designated QR code with their mobile device, and the application will place a virtual 3D model (a "Stupa") into their real-world environment, anchored to the position of the code.
This project serves as an exploration of fundamental AR concepts, including image tracking, session management, and user interaction in a mixed-reality space.

## 2\. Core Functionality
*   **QR Code Scanning:** The app initiates its AR experience by scanning a specific QR code.
*   **Image Reference Library:** The QR code functions as a reference image. The app uses its metadata and tracked position to determine where to place the virtual object.
*   **Real-Time Object Placement:** Once the code is detected, the app instantiates a virtual object in real-time at the code's location in the Cartesian plane.
*   **Simple User Interface:** A straightforward UI welcomes the user and guides them to the scanning action.

## 3\. Key Technical Components
This application is built using several key components common in AR development:
*   **XR Origin:** The central manager for the AR/VR application. It is responsible for AR image tracking and handling the placement of virtual objects within the perceived world.
*   **AR Session:** Manages the overall AR experience, including processing input from the device's camera and handling the lifecycle of the AR session.
*   **XR Camera:** The virtual camera that captures the real-time images from the device, allowing the user to "see" the virtual objects overlaid on their environment.

## 4\. How It Works: User Flow
1.  **Welcome Screen:** The user opens the app to a simple welcome UI.
2.  **Scan Action:** The user points their device's camera at the designated QR code.
3.  **Detection & Placement:** The `AR Session` and `XR Origin` work together to detect the QR code as a tracked image.
4.  **Instantiation:** The application processes this data and instantiates the virtual "Stupa" model, anchoring it to the QR code's position.
5.  **Interaction:** The user can then move their device around to view the virtual object from different angles as it remains fixed in the real-world location.

## 5\. Target Audience
This project and its documentation are suitable for:
*   Developers new to AR frameworks.
*   Students and enthusiasts interested in AR technology.    
*   Anyone looking to understand the mechanics of image tracking and real-time object placement in AR.
## 6\. Demonstration

A live demonstration on a mobile device is the best way to understand the application's functionality, showcasing the user interface and the real-time AR object rendering in action: [Youtube](https://www.youtube.com/watch?v=Pj2WlW6fBN0)
