# Privacy Policy — NoAds

**Effective date:** 2026-08-17
**App:** NoAds (package `dev.noads.app`)
**Developer contact:** maynax@gmail.com

This Privacy Policy explains what information the NoAds app collects, how it is used, and the choices available to you. By using NoAds you agree to the terms below.

## 1. Information We Collect

NoAds is designed to work with the minimum data required to function. We do **not** collect names, emails, phone numbers, contacts, photos, location, or any other personally identifiable information ourselves.

The following categories of data are processed:

### 1.1 Device and diagnostic data (via Google Firebase)
- **Firebase Remote Config** — used to deliver version, maintenance, and configuration flags. Firebase may log anonymous instance identifiers (Firebase Installation IDs), coarse app version, OS version, device model, and language.
- **Firebase App Check (Play Integrity)** — verifies that the app is genuine and running on a genuine Android device. Google Play services generate an integrity token for this check.
- Firebase processing is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

### 1.2 Advertising data (via Google AdMob)
- The app displays ads served by **Google AdMob**. AdMob and its partners may collect device identifiers (such as the Android Advertising ID), IP address, coarse location derived from the IP, and interaction data with the ads.
- Ads may be **personalized** based on this data unless you opt out. When required by law, a consent form is shown before personalized ads are served.
- Full details: [Google AdMob & AdSense Privacy Policy](https://policies.google.com/technologies/ads).
- You can reset or opt out of the Advertising ID from **Android Settings → Google → Ads**.

### 1.3 Purchase data (via Google Play Billing)
- If you purchase the "Remove Ads" upgrade, the transaction is handled by Google Play. NoAds only receives a purchase token that proves the entitlement.
- The purchase status is stored **locally on your device** using Android encrypted storage (`flutter_secure_storage`). We do not receive your payment details.

### 1.4 Permissions used
- `INTERNET`, `ACCESS_NETWORK_STATE` — required for Firebase, ads, and updates.
- `QUERY_ALL_PACKAGES` — needed so the launcher can list installed apps you may want to interact with.
- `SYSTEM_ALERT_WINDOW`, `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_SPECIAL_USE` — required for the floating overlay button.
- `PACKAGE_USAGE_STATS` — used only to detect which app is currently in the foreground so the overlay behaves correctly. Nothing is transmitted off-device.
- `KILL_BACKGROUND_PROCESSES` — used to close ad SDK processes when you tap the toggle.

## 2. How We Use the Information

- Deliver core app functionality (overlay button, ad-related actions).
- Verify app integrity and block tampered builds.
- Serve advertisements and, if purchased, remove them.
- Deliver critical updates and enforce minimum supported version.

We do **not** sell, rent, or share personal information with third parties beyond the service providers listed above (Google Firebase, Google AdMob, Google Play Billing).

## 3. Children

NoAds is **not directed to children under 13**. We do not knowingly collect data from children. If you believe a child has used the app, contact us and we will assist in removing any associated data held by our service providers.

## 4. Data Retention

- On-device data (secure storage, preferences) remains on your device until you uninstall the app or clear its storage.
- Firebase Installation IDs and AdMob identifiers follow the retention policies of Google as described in their respective privacy policies.

## 5. Your Rights

Depending on your jurisdiction (GDPR, CCPA, or equivalent), you may have rights to access, correct, or delete data held about you. Because NoAds itself does not hold personal data on its own servers, most requests should be directed to Google for the Firebase / AdMob / Play data mentioned above. For anything related to the app itself, email us at **maynax@gmail.com**.

## 6. Changes to This Policy

We may update this Privacy Policy from time to time. The latest version is always available at:

<https://github.com/0xR0/noads/blob/main/PRIVACY.md>

Material changes will be communicated in-app or via the store listing.

## 7. Contact

Questions or requests: **maynax@gmail.com**
