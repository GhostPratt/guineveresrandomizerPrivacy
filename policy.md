# Privacy Policy for Guinevere's Randomizer

**Last Updated:** January 2025

## Introduction

Guinevere's Randomizer ("we", "our", or "the app") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and safeguard your information when you use our Android application.

## Information We Collect

### 1. Information You Provide

**Account Information (Optional)**
- When you choose to sign in with Google, we collect:
  - Your Google account email address
  - Google user ID
  - Authentication tokens

**User-Created Content**
- Custom list names and items
- Number range presets
- App preferences and settings

### 2. Automatically Collected Information

**Local Storage**
- Lists and randomization data stored locally on your device
- App preferences (theme settings, display preferences)
- Usage metrics for in-app review prompts (launch count, action count, review request timestamps)

**Crash Reports**
- We use Firebase Crashlytics to collect crash reports and error logs
- This includes device information, app state, and stack traces
- This data helps us identify and fix bugs to improve app stability

**Network Connectivity**
- The app checks network availability to determine whether to use online or offline randomization

## How We Use Your Information

### Core Functionality
- **Random Number Generation**: Generate random numbers and shuffle lists
- **List Management**: Store and organize your custom lists
- **Cloud Sync**: Synchronize your data across devices (when signed in)
- **Theme Customization**: Save and apply your preferred app theme

### App Improvement
- **Crash Analysis**: Identify and fix bugs using Crashlytics data
- **User Feedback**: Request in-app reviews based on usage patterns

## Third-Party Services

### Firebase Services (Google)
We use the following Firebase services:

**Firebase Authentication**
- Purpose: Enable optional Google Sign-In
- Data collected: Google email, user ID, authentication tokens
- Privacy Policy: https://firebase.google.com/support/privacy

**Firebase Firestore**
- Purpose: Cloud storage for syncing data across devices (optional)
- Data stored: Lists, number ranges, and app settings
- Data access: Only accessible by the authenticated user
- Privacy Policy: https://firebase.google.com/support/privacy

**Firebase Crashlytics**
- Purpose: Crash reporting and error tracking
- Data collected: Crash logs, device information, app state
- Privacy Policy: https://firebase.google.com/support/privacy

### Random.org API
- Purpose: Generate true random numbers from atmospheric noise
- Data sent: Randomization parameters (min, max, count)
- No personal information is sent to Random.org
- The app automatically falls back to local randomization if the API is unavailable
- Privacy Policy: https://www.random.org/privacy/

### Google Play Services
- Purpose: In-app review functionality, Google Sign-In, and in-app subscriptions
- Data collected: Review interactions, authentication data, purchase information
- Privacy Policy: https://policies.google.com/privacy

### Google Play Billing
- Purpose: Process subscription payments for Cloud Sync Premium
- Data collected: Purchase history, subscription status, payment tokens
- Google handles all payment processing; we only receive subscription status
- Privacy Policy: https://payments.google.com/payments/apis-secure/get_legal_document?ldo=0&ldt=privacynotice

## Data Storage and Security

### Local Storage
- All data is stored locally on your device by default using encrypted SQLite database
- Local data persists until you uninstall the app or clear app data

### Cloud Storage (Optional - Requires Subscription)
- Cloud sync is **only active when you sign in with Google AND subscribe to Cloud Sync Premium**
- Subscription-based feature to sync your data across devices
- Data is stored in Firebase Firestore with user-specific security rules
- Only you can access your cloud-stored data
- Data is encrypted in transit using HTTPS/TLS

### Data Retention
- **Local Data**: Retained until you uninstall the app or clear app data
- **Cloud Data**: Retained until you delete your data or sign out
- **Crash Logs**: Retained by Firebase Crashlytics for 90 days

## Your Privacy Rights

### Data Access and Control
- **View Your Data**: All lists and settings are visible within the app
- **Export Your Data**: Use the import/export feature to save your lists
- **Delete Your Data**:
  - Local data: Uninstall the app or clear app data in Android settings
  - Cloud data: Sign out to stop syncing; data can be deleted by uninstalling the app
- **Cancel Subscription**: Manage your subscription through Google Play Store settings

### Opt-Out Options
- **Google Sign-In**: Signing in is completely optional; all core features work offline
- **Cloud Sync**: Don't subscribe to Cloud Sync Premium to avoid cloud storage
- **Subscriptions**: You can cancel your subscription anytime through Google Play Store
- **Crash Reports**: Cannot be disabled (required for app stability improvements)

## Permissions

The app requests the following Android permissions:

- **INTERNET**: Required for Random.org API, Firebase services, and Google Sign-In
- **ACCESS_NETWORK_STATE**: Required to check network connectivity and determine when to use offline mode

## Children's Privacy

This app does not knowingly collect personal information from children under 13. If you are a parent or guardian and believe your child has provided personal information, please contact us.

## Data Sharing

We do not sell, trade, or rent your personal information to third parties. Your data is only shared with:

- **Firebase/Google**: For authentication and cloud sync (when you subscribe)
- **Google Play Billing**: For processing subscription payments
- **Random.org**: Randomization parameters only (no personal information)

## Subscriptions and Payments

### Cloud Sync Premium Subscription
- **Billing**: Processed securely through Google Play Billing
- **Payment Information**: We do not have access to your payment details (credit card, etc.)
- **Subscription Status**: We only receive notification of active/inactive subscription status
- **Cancellation**: Cancel anytime through Google Play Store; access continues until the end of billing period
- **Refunds**: Subject to Google Play Store refund policy
- **Auto-Renewal**: Subscriptions auto-renew unless cancelled before renewal date
- **Data After Cancellation**: Cloud data remains accessible for 30 days after cancellation, then may be deleted

## Analytics

The app does **not** use Google Analytics, Firebase Analytics, or any third-party analytics services. The only tracking is:

- Local usage metrics for in-app review prompts (launch count, action count)
- Crash reports via Firebase Crashlytics

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date at the top of this policy
- Posting the new Privacy Policy in the app repository

## International Data Transfers

If you use this app outside the United States, please be aware that your data may be transferred to, stored, and processed in the United States where Firebase servers are located.

## Contact Information

If you have questions or concerns about this Privacy Policy or our data practices, please contact us at:

**Email**: guineveressoftware@gmail.com
**GitHub**: https://github.com/[your-username]/GuineveresRandomizerApp

## Compliance

This app complies with:
- Google Play Store policies
- Firebase/Google Cloud Platform terms of service
- General Data Protection Regulation (GDPR) principles
- California Consumer Privacy Act (CCPA) principles

## Your Consent

By using Guinevere's Randomizer, you consent to this Privacy Policy.

---

## Summary (TL;DR)

✅ **No account required** - App works fully offline without sign-in
✅ **Premium cloud sync** - Subscribe to Cloud Sync Premium for cross-device sync
✅ **Local-first storage** - All data stored on your device by default
✅ **No ads or tracking** - No analytics, no advertising networks
✅ **Minimal permissions** - Only INTERNET and network state access
✅ **Crash reporting** - Firebase Crashlytics to fix bugs and improve stability
✅ **Third-party APIs** - Random.org for true random numbers (with offline fallback)
✅ **Secure payments** - Subscriptions handled by Google Play Billing
✅ **Cancel anytime** - Full refund control through Google Play Store
✅ **Your data is yours** - Export lists, delete anytime, no vendor lock-in
