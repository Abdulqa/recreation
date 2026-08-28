# Privacy Policy for Notification Vault

**App name:** Notification Vault
**Developer:** Recreation Technologies Team
**Effective date:** 28 August 2026
**Last updated:** 28 August 2026

This Privacy Policy explains how the **Recreation Technologies Team** ("we", "us", "our") handles information in connection with the **Notification Vault** mobile application (the "App"). Notification Vault keeps a private, on-device history of the notifications your device receives so you can search, filter, and revisit them. We designed the App to collect as little information as possible.

> **Summary:** Notification Vault does **not** require an account or sign-in. The App has **no internet permission** and is technically incapable of uploading anything. Your notification history is stored only on your own device and is never sent to us or any third party. There are no ads, no analytics, and no third-party tracking SDKs.

## 1. Information We Process

### 1.1 Information stored only on your device
To do its job, the App uses Android's **Notification Access** permission (`BIND_NOTIFICATION_LISTENER_SERVICE`). While you have granted that permission, the App reads notifications posted on your device and stores the following in a private database that only the App can read:

- The posting app's package name and label
- The notification title and text
- The timestamp
- Small facts the App derives locally on your device: a category guess (message, OTP, transaction, promotion, alert, system, other), a flag for whether the content looks sensitive, and a hash used to detect duplicate notifications

This information stays on your device, is never transmitted to us, and is deleted when you clear your history or uninstall the App.

### 1.2 Information the App does **not** access
The App does not access your contacts, location, camera, microphone, files, call logs, or SMS, and it uses no account. It queries the system only for the icon and name of apps that have sent you a notification.

### 1.3 Information collected automatically
None. The App contains no advertising SDK, no analytics SDK, and no crash-reporting SDK. We operate no servers and receive no data from the App. If the App crashes, a technical log (a stack trace, containing no notification content) is written to the App's private storage on your device; nothing is sent unless you manually choose to export and share it with us.

## 2. How We Use Information

| Data | Purpose |
| --- | --- |
| Notification content stored on your device | To display your searchable notification history inside the App, on your device only |
| Locally derived category / sensitivity / duplicate-hash | To group, filter, and mask entries inside the App |

We do not use your information for any other purpose because your information never reaches us.

## 3. Data Sharing and Disclosure

We do not share, sell, or disclose your information, because we do not have it. Nothing leaves your device through the App.

If you use the App's **Export** feature, the App writes a CSV, JSON, or plain-text copy of your history to a location you choose through the Android system file picker. After that, the exported file is under your control and this policy no longer governs it.

## 4. Data Retention and Deletion

- You choose a retention policy in the App: automatically delete history older than 7, 30, 90 days, or 1 year, or keep it forever.
- Deleted entries are purged permanently after a short undo window.
- **Settings ▸ Storage ▸ Clear all** deletes the entire history immediately.
- Uninstalling the App removes all of its data from your device.
- Automatic device backup is disabled for the App (`android:allowBackup="false"`), so your history is not included in Google cloud backups.

## 5. Security

Captured data is held in the App's private storage, an area Android isolates from other apps and encrypts at rest on modern devices. Because the App has no network capability, there is no transmission to intercept. You can additionally enable an app-lock that requires your device biometric or PIN to open the App.

## 6. Permissions

| Permission | Why | Optional? |
| --- | --- | --- |
| Notification access (`BIND_NOTIFICATION_LISTENER_SERVICE`) | Read notifications to build your history — the core function of the App | You grant it manually and can revoke it any time in system settings |
| Biometric (`USE_BIOMETRIC`) | The optional app-lock screen | Yes — only used if you enable app lock |

The App requests **no** internet, storage, location, contacts, or other sensitive permissions.

## 7. Children's Privacy

Notification Vault is not directed to children and does not knowingly collect personal information from children. It is a utility app intended for general audiences aged 18+.

## 8. On-Device Assistant

The App includes an optional assistant that answers questions about your history (for example, "did I get an OTP yesterday?"). It runs entirely on your device against the local database. No question and no notification content is sent anywhere.

## 9. Changes to This Policy

If the App's behaviour changes in a way that affects this policy, we will update this document and change the "Last updated" date. Material changes will also be noted in the App's release notes.

## 10. Contact Us

If you have questions or requests regarding this Privacy Policy or your data, contact us at:

**Recreation Technologies Team**
Email: recreationtechnologies@gmail.com

---

© 2026 Recreation Technologies Team. All rights reserved. Notification Vault is an independent application and is not affiliated with Google LLC or any notification-sending service.
