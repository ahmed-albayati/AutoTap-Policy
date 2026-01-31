# Privacy Policy for Auto Tap

**Effective Date:** February 1, 2026  
**Last Updated:** February 1, 2026

**Ahmed** (the "Developer", "we", "us", or "our") built the **Auto Tap** mobile application (the "App" or "Service") as a **free utility application**. This SERVICE is provided **at no cost** and is intended for use **as is**.

This page is used to inform visitors / users regarding our policies with the collection, use, storage, sharing and disclosure of Personal Information (if any) when anyone decides to use our Service.

**By using the App, you agree to the collection and use of information in accordance with this policy.** If you do **not** agree with this Privacy Policy, please do not use the App.

### 1. Information We Collect

**We do NOT collect, store, transmit or share any personal information.**

The App does **not**:

- Require account creation
- Ask for email, name, phone number or any identifying information
- Collect device identifiers (IMEI, advertising ID, etc.) for tracking purposes
- Upload or send any user data to remote servers
- Use analytics services that track individual users (Firebase Analytics, Google Analytics for Firebase, etc. — if not explicitly added)
- Contain advertisements (if no ads are implemented)
- Use crash reporting that sends personally identifiable data

The only permissions the App requests are:

- **Accessibility Service** (BIND_ACCESSIBILITY_SERVICE)  
  → Used exclusively to simulate screen taps, clicks and gestures at user-specified screen coordinates when you actively start the auto-clicker.

- **SYSTEM_ALERT_WINDOW** ("Draw over other apps")  
  → Used to display the floating control bubble / overlay panel and draggable click markers.

- **VIBRATE** (optional)  
  → Used only for optional haptic feedback when buttons are pressed.

**No screen content is read, recorded or transmitted.**  
The Accessibility Service is used **only** to dispatch the exact gestures (tap / click) that **you** configure inside the App. We do **not** read screen text, UI hierarchy, window titles, or any other content.

### 2. How We Use the Accessibility Service

We use the **AccessibilityService** API **only** for the core functionality of the App:

- Performing automated single taps or click sequences at the exact (x,y) coordinates you select
- Supporting multi-point clicking, intervals, repeat modes, and stop conditions **as configured by you**
- Showing visual markers and floating controls **on your device only**

**We do not:**

- Monitor your activity
- Record your screen
- Capture keystrokes, passwords, messages, photos, or any other content
- Send any accessibility events or node information to any server
- Use the service for purposes other than auto-tapping / auto-clicking as explicitly started by you

### 3. Data Storage

- All click positions, intervals, patterns, repeat settings and history sessions are stored **locally on your device only** using:
  - AsyncStorage (React Native)
  - Local file / database (if implemented)

- No data is ever uploaded to any cloud service, server, or third-party backend.
- You can delete all local data by clearing app data or uninstalling the App.

### 4. Third-Party Services

Currently the App does **not** integrate any third-party services that collect data (no ads, no analytics, no crashlytics, no cloud sync).

If this changes in a future version, this section will be updated and a new version of this Privacy Policy will be published.

### 5. Children's Privacy

The App is **not** directed to children under the age of 13 (or 16 in some jurisdictions).  
We do **not** knowingly collect personal information from children.  
If we become aware that a child has provided us with personal information, we will delete it immediately.

### 6. Changes to This Privacy Policy

We may update our Privacy Policy from time to time.  
We will notify users of any material changes by updating the "Last Updated" date at the top of this page.  
You are advised to review this Privacy Policy periodically for any changes.

### 7. Contact Us

If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us:

- Email: **[your-email-here@example.com]** (replace with real email if you have one)
- GitHub: https://github.com/[your-username]/AutoTap (or wherever your repo is)

---

**Auto Tap** is developed and maintained independently.  
We are committed to your privacy and to providing a transparent, minimal-data-collection utility tool.

Thank you for using Auto Tap!
