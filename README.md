# Privacy Policy for Cube Solver XR

**Effective Date:** October 3, 2026  
**Application Name:** Cube Solver XR  
**Package Name:** `com.cubesolverxr.app`  

---

### Overview

Cube Solver XR ("the Application", "we", "us", or "our") is designed from the ground up to respect and protect your privacy. We believe that spatial computing applications should process your sensory and physical environment locally. 

**Cube Solver XR does not collect, transmit, sell, or store any personal data or camera feeds on external servers.** All computer vision, voice recognition, and hand tracking operations are performed **100% locally on your device in real-time**.

---

### 1. Information Processing & Permissions

Cube Solver XR requires specific hardware permissions to deliver its spatial computing and puzzle-solving features. Below is a detailed description of how each permission is used:

#### A. Camera Access (`android.permission.CAMERA`)
* **Purpose:** Used strictly to scan and detect the colors of physical puzzle cube faces.
* **Processing:** Video frames are analyzed in temporary memory (RAM) in real time using local computer vision algorithms to determine cube face colors.
* **Storage & Sharing:** **Zero camera data is saved or recorded.** No images, photos, or video streams are ever stored to local disk, transmitted over the internet, or shared with third parties. Once the cube colors are resolved, camera frames are immediately discarded from memory.

#### B. Microphone Access (`android.permission.RECORD_AUDIO`)
* **Purpose:** Used solely for hands-free voice commands (such as "scramble", "solve", or "reset") while you interact with physical or virtual cubes.
* **Processing:** Audio signals are processed locally on the device using real-time speech recognition.
* **Storage & Sharing:** **Zero audio data is recorded or stored.** Audio buffers are transient and are not sent to any cloud server or third-party service.

#### C. Hand Tracking & Spatial Sensors (`android.permission.HAND_TRACKING`)
* **Purpose:** Utilized by Android XR and SceneCore to allow natural pinch, hover, and tap interactions with the virtual 3D speed mat, timer buttons, and spatial interface.
* **Processing:** Hand skeletal tracking and spatial coordinate transforms remain within the local operating system session.
* **Storage & Sharing:** Spatial coordinates are never saved, logged, or transmitted off your headset.

---

#### D. Creator Referral Attribution & Internet Access (`android.permission.INTERNET`)
* **Purpose:** Allows the application to credit content creators and affiliates who refer users to purchase the application via the official Google Play Install Referrer API.
* **Processing:** On first launch, the app reads the campaign referral parameter provided by Google Play (e.g., `creator=alex`). A one-time webhook payload containing the referral identifier, install timestamp, and device model is sent to the developer's private accounting ledger.
* **Privacy:** No personal identifying information (PII), names, email addresses, phone numbers, or user location are collected or transmitted.

---

### 2. Data Storage & Retention

* **Local App Storage:** The Application stores personal solve history, session averages (Ao5, Ao12), and custom cube schemes locally on your device.
* **Offline Cross-Device Sync:** Data can be transferred between headsets and phones using offline optical QR codes without any remote cloud servers.
* **Cloud Storage:** None. We operate no cloud user database or analytics tracking.
* **Data Deletion:** Uninstalling the Application or clearing app storage in Android Settings permanently removes all locally stored solve times and preferences.

---

### 3. Third-Party Services & SDKs

* **No Advertising SDKs:** Cube Solver XR contains no third-party ad networks, trackers, or commercial data brokers.
* **No Telemetry:** We do not track user behavior or sell user data.

---

### 4. Children’s Privacy

Cube Solver XR is a family-friendly utility and puzzle-solving application suitable for users of all ages. We do not knowingly collect or solicit personal information from children under the age of 13 (or 16 in the European Union), in full compliance with the Children’s Online Privacy Protection Act (COPPA) and GDPR. Because no personal data is collected from any user, children’s privacy is inherently protected.

---

### 5. Security

Because all processing occurs strictly on your device and no data is transmitted over the internet, your information is protected from remote transmission interception. We adhere to industry best practices and Android platform security guidelines.

---

### 6. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected on this page with an updated "Effective Date". We encourage you to review this policy periodically.

---

### 7. Contact & Support

We welcome your questions, feedback, bug reports, and feature suggestions:

* **App Name:** Cube Solver XR
* **In-App Support:** Open **Cube Solver XR** on your device, navigate to the dashboard or settings menu, and select **Report Issue** or **Request Feature** to submit feedback directly to the developer team.
