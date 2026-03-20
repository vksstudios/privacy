# Privacy Policy for Pingora

**Effective Date: March 20, 2026**

Pingora ("we," "us," or "our") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and safeguard your information when you use our website monitoring application and mobile app.

---

## 1. Information We Collect

We only collect data that is essential for providing our heartbeat monitoring and alerting services.

### A. Account Information
*   **Email Address**: Used for account identification, secure login, and sending downtime alerts.
*   **Passwords**: We store only cryptographically hashed versions of your passwords using industry-standard (Bcrypt) encryption. We never see or store your raw password.

### B. Monitoring Data
*   **Website URLs**: To monitor your fleet, we store the target URLs you provide.
*   **Response Metrics**: We record HTTP status codes, response times (latency), and error messages to generate your health reports.
*   **SSL Status**: Metadata about your SSL certificates (expiry dates) to provide renewal alerts.

### C. Technical Identifiers
*   **FCM Tokens**: For users on Android or iOS, we store specialized tokens (Firebase Cloud Messaging) to deliver instant push notifications to your device.
*   **JWT Tokens**: We use secure session tokens to keep you logged into your "Cockpit" without storing credentials in your browser.

---

## 2. How We Use Your Data

*   **Service Delivery**: To ping your websites at your requested intervals (60s, 300s, 600s).
*   **Real-time Alerting**: To notify you via Email or Push Notification the moment a "Frequency Loss" (downtime) is detected.
*   **Audit Reporting**: To generate the "Fleet Audit" reports you request.
*   **System Optimization**: We use log data to improve the speed and accuracy of our monitoring worker.

---

## 3. Data Retention & The "Purge" Principle

We believe you should own your data. Our unique **"Audit & Purge"** feature allows you to:
1.  Generate a full snapshot of your monitor history.
2.  Receive that record via a secure email.
3.  Immediately wipe that history from our primary database.

Once purged, those logs are permanently deleted from our terminal and cannot be recovered.

---

## 4. Security Measures

*   **Encryption at Rest**: All sensitive data is stored in a secure PostgreSQL environment.
*   **Encryption in Transit**: All communication between the web/mobile app and our API is performed over SSL/TLS.
*   **Biometric Security**: On mobile devices, we support FaceID/Fingerprint authentication for app entry. Note: Pingora **does not** store your biometric data; this is handled locally by your device's hardware.

---

## 5. Third-Party Sharing

We **do not** sell, trade, or rent your personal information to third parties. We only share data with service providers necessary for technical operations:
*   **SMTP Providers**: To deliver your alert emails.
*   **Firebase**: To deliver native push notifications to your mobile device.

---

## 6. Your Rights

You have the right to access, correct, or delete your account at any time. Terminating your secure session and deleting a monitor will remove all associated check history from our systems.

---

## 7. Contact Us

For any questions regarding this Privacy Policy or your data, please contact the VKS Studios Security Team.
