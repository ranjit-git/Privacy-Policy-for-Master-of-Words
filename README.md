
# Privacy Policy for Master of Words: Word puzzle

**Effective Date:** 29/7/26

This Privacy Policy applies to the **Master of Words: Word puzzle** mobile application (the "App"), developed by **Ranjit Pahan** ("we", "us", or "our"). 

We are committed to respecting and protecting your privacy. This policy explains what information the App collects, how it is used, how it is secured, and your rights when you play Master of Words.

---

## 1. Information We Collect

Master of Words is designed with an offline-first architecture. We do not require you to create an account with us, nor do we operate proprietary external servers to collect, store, or sell your personal details. 

However, to provide gameplay features, advertisements, and stability monitoring, the App uses local storage and industry-standard third-party SDKs.

### A. Locally Stored Data (On Your Device)
Your progress and configuration are stored locally on your device:
* **Game Progress & Economy:** Current chapter, completed levels, stars earned, total bonus words found, and current gem balance.
* **Preferences:** Audio toggles (music, sound effects, UI clicks), haptic feedback settings, and selected language.
* **Security & Storage:** All sensitive local data is stored in a structured local database encrypted at rest using **AES-256 encryption**.
* **Transmission:** We do not transmit or copy your local game save data to external personal servers.

### B. Local Notifications
The App utilizes device-level scheduling to deliver local reminders (e.g., notifying you when your Daily Reward is ready to claim or to keep your daily streak alive):
* On devices running Android 13 or higher, the App requests the `POST_NOTIFICATIONS` permission.
* These notifications are generated and scheduled entirely **on your device**; no personal information or device tokens are sent to external push messaging servers.

### C. Automatically Collected Data (Third-Party Services)
When you use the App with an active internet connection, third-party services collect certain technical and usage information:
* **Device Identifiers:** Device model, operating system version, carrier, and unique device identifiers (such as Google Advertising ID / AAID or Apple IDFA, and Firebase Installation IDs).
* **App Activity & Gameplay Analytics:** Anonymous event data regarding your in-game interactions (e.g., levels started, levels cleared, hints used, bonus words discovered, rewarded ads watched, and app sessions) logged via Firebase Analytics.
* **Crash & Diagnostic Logs:** Anonymous stack traces, system state at the time of a crash, and diagnostic performance metrics collected via Firebase Crashlytics.
* **Advertising Data:** Information regarding ad impressions, clicks, video views, and IP addresses used by Google AdMob to serve ads and detect fraud.

---

## 2. Third-Party Services & Integrations

The App integrates trusted third-party services that process data in accordance with their respective privacy policies:

* **Google Mobile Ads (AdMob):** Serves banner, interstitial, and rewarded video ads that keep the game free to play.
  * [Google Privacy & Terms](https://policies.google.com/privacy)
  * [Google AdMob Information](https://policies.google.com/technologies/ads)
* **Google Firebase (Analytics & Crashlytics):** Analyzes gameplay trends to help us balance puzzle difficulty and logs crash reports to resolve technical bugs.
  * [Firebase Privacy and Security](https://firebase.google.com/support/privacy)
* **Google Play Games Services / Apple Game Center (Optional):** Provides cloud achievements and global leaderboards. If you sign in, authentication and score records are handled directly by Google or Apple; we do not store your account passwords or personal profiles on custom servers.
  * [Google Play Games Terms](https://policies.google.com/privacy)
  * [Apple Privacy Policy](https://www.apple.com/legal/privacy/)

---

## 3. In-App Purchases & Financial Data

Master of Words offers optional in-app purchases (e.g., gem packages and an ad-free premium unlock):
* All payments are processed directly by **Google Play Billing** (on Android) or **Apple StoreKit** (on iOS).
* **We do not collect, process, or store credit card numbers, bank details, or billing addresses.** 
* We only receive an encrypted receipt/token from the platform store confirming that the transaction was successful so the App can credit your gems or remove ads.

---

## 4. How We Use Your Information

The data collected is utilized strictly for the following purposes:
1. **Core Gameplay & Delivery:** Maintaining your local progress, awarding puzzle achievements, and crediting rewarded gems.
2. **Monetization:** Displaying banner, interstitial, and rewarded ads to support ongoing development.
3. **Analytics & Game Balancing:** Understanding player completion rates and puzzle difficulty to improve future levels.
4. **Diagnostics & Bug Fixing:** Identifying crashes across diverse Android device configurations.
5. **Security & Fraud Prevention:** Detecting ad manipulation, invalid clicks, and bot activity.

---

## 5. Data Security & Encryption

We prioritize safeguarding your information:
* **Encrypted in Transit:** All communications between the App and third-party services (AdMob, Firebase, Google Play) are encrypted in transit using industry-standard **HTTPS/TLS (Transport Layer Security)** protocols.
* **Encrypted at Rest:** Your local game progress and sensitive settings are secured on your device using **AES-256 encryption**.

---

## 6. Your Rights, Consent & Data Deletion

Depending on your jurisdiction (such as the European Economic Area, UK, or California), you have legal rights regarding your data:

### A. European Privacy & Consent (GDPR / UMP)
* When launching the App in applicable regions, you will be presented with a consent form powered by the Google User Messaging Platform (UMP) to accept or decline personalized advertisements.
* **In-App Revocation:** You can change or revoke your consent preferences at any time by going to the in-game **Settings** menu and selecting **"GDPR Privacy Options"**.

### B. Opt-Out via Device Settings
You can opt out of personalized advertisements across all apps via your device's operating system:
* **Android:** Open *Settings* > *Google* > *Ads* > *Delete advertising ID* or *Opt out of Ads Personalization*.
* **iOS:** Open *Settings* > *Privacy & Security* > *Tracking* > Disable tracking permissions.

### C. Complete Data Deletion
Because we do not operate a remote server hosting your account or profile, you have immediate, direct control over your stored data:
* **In-App Reset:** You can instantly and permanently erase all saved progress, level stars, and gem balances by tapping **"Erase and Reset All Data"** in the **Danger Zone** section of the in-game Settings menu.
* **App Uninstall:** Uninstalling the App permanently deletes all local files, databases, and cryptographic keys from your device.

---

## 7. Children’s Privacy (COPPA & GDPR-K)

Master of Words is intended for a general audience (ages 13 and older). We do not knowingly collect or solicit personally identifiable information from children under the age of 13 (or under 16 in the European Economic Area). 

If we learn that we have inadvertently received personal information from a child under 13 without verified parental consent, we will take immediate steps to delete that information. If you are a parent or guardian and believe your child has provided us with personal information, please contact us immediately.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or applicable legal requirements. Any modifications will be posted to this page with an updated "Effective Date". We encourage you to review this policy periodically.

---

## 9. Contact Us

If you have any questions, feedback, or concerns regarding this Privacy Policy or your data, please contact us at:

* **Developer:** Ranjit Pahan
* **Email:** pahan.ranjit.0201@gmail.com
* **Project Repository / Hosting:** https://ranjit-git.github.io/Privacy-Policy-for-Master-of-Words/
