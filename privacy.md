---
layout: default
title: Privacy Policy
---

# Privacy Policy

**Effective date:** [LAUNCH DATE]
**Last updated:** [LAUNCH DATE]

This Privacy Policy describes how Ventaglio ("we", "us", or "the app") handles your information. By using Ventaglio, you agree to the terms described here.

[← Back to home](./)

## Who we are

Ventaglio is an independent iOS and watchOS app built for beach tennis players to track performance metrics during matches. The app is developed by Nikolas Mesquita do Nascimento as an individual developer.

## What information we collect

### Information you provide directly

When you sign in to Ventaglio using Google Sign-In, we receive:

- Your **name** (display name from your Google account)
- Your **email address**
- A **unique user identifier** (Firebase user ID, used internally to associate your data with your account)

When you complete the onboarding screen, you also provide:

- Your **player skill level** (beginner, intermediate, or advanced)
- Your **dominant hand** (right or left)

This profile information is stored **only on your device** and is not transmitted to any server.

### Information collected automatically during use

During an active beach tennis session on your Apple Watch, the app collects:

- **Heart rate** (via HealthKit)
- **Active energy burned** (via HealthKit)
- **Step count** (via HealthKit)
- **Distance traveled** (via HealthKit and Core Location / GPS)
- **Precise location** (only while you are actively using the app, to measure distance covered on outdoor courts)

This data is collected only while you have an active workout session running.

## How we use your information

Your information is used solely to provide the app's core functionality:

- Display your match metrics in real time on the Apple Watch
- Save your match history on your iPhone for later review
- Save matches to the iOS Health app as workouts (if you grant permission)
- Authenticate you across sessions and devices

We do **not** use your information for:

- Advertising
- Tracking across other apps or websites
- Profiling or behavioral analytics
- Marketing communications

## Where your information is stored

| Data | Location |
|---|---|
| Profile (name, skill level, dominant hand) | On your device (SwiftData, local) |
| Match metrics (heart rate, calories, steps, distance) | On your device (SwiftData, local) |
| Authentication credentials (Google account, user ID) | Firebase Authentication servers (Google Cloud) |
| Health data (if you save matches as workouts) | iOS Health app on your device |

**Match data is never transmitted to our servers or third parties.** It exists only on your iPhone and Apple Watch, and is synchronized between them via Apple's WatchConnectivity framework.

The only data that leaves your device is your Google authentication, which goes directly to Firebase Authentication (operated by Google) for the sole purpose of verifying your identity.

## Third-party services

Ventaglio uses the following third-party services:

### Google Sign-In and Firebase Authentication

We use Google Sign-In to authenticate users. When you sign in:

- Google handles the authentication
- Firebase Authentication (Google Cloud) stores your authentication credentials
- We receive your name, email, and a user ID from this process

Google's privacy policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)
Firebase privacy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### Apple HealthKit and Core Location

These are Apple system services. Data accessed via HealthKit and Core Location is governed by Apple's privacy policies and remains under your control through iOS Settings.

Apple's privacy policy: [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)

## Your rights

Depending on your jurisdiction, you may have the following rights:

### Under GDPR (European Union)

- Right to access your data
- Right to correct inaccurate data
- Right to delete your data ("right to be forgotten")
- Right to data portability
- Right to object to processing
- Right to lodge a complaint with a supervisory authority

### Under LGPD (Brazil)

- Right to confirm data processing
- Right to access your data
- Right to correct incomplete or inaccurate data
- Right to anonymize, block, or delete unnecessary data
- Right to data portability
- Right to delete data processed with your consent
- Right to information about data sharing
- Right to revoke consent

### How to exercise your rights

To exercise any of these rights, contact us at [support@ventaglio.app](mailto:support@ventaglio.app).

### Deleting your data

- **Match data and profile:** uninstall the app from your iPhone and Apple Watch. All local data is permanently deleted.
- **Authentication account:** email us at [support@ventaglio.app](mailto:support@ventaglio.app) requesting account deletion. We will delete your Firebase Authentication record within 30 days.

## Data retention

- **Local data (profile, matches):** retained on your device until you delete the app or manually delete entries.
- **Authentication data:** retained on Firebase until you request account deletion.

## Children's privacy

Ventaglio is not directed to children under 13. We do not knowingly collect data from children under 13. If you become aware that a child has provided us with personal information, please contact [support@ventaglio.app](mailto:support@ventaglio.app).

## Security

We use industry-standard security practices:

- All communication with Firebase Authentication is encrypted via HTTPS/TLS
- Local data is protected by iOS data protection and your device passcode
- We do not store passwords (authentication is handled by Google)

## Changes to this policy

We may update this Privacy Policy. The "Last updated" date at the top reflects the most recent revision. Material changes will be communicated through the app.

## Contact

Questions or requests regarding this Privacy Policy:

**Email:** [support@ventaglio.app](mailto:support@ventaglio.app)

---

[← Back to home](./) · [Política de Privacidade (Português)](./privacy-pt)
