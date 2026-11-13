# Privacy Policy for Master of Words: Word puzzle

**Effective Date:** 29/7/26  
**Last Updated:** 14/11/26  

This Privacy Policy applies to the **Master of Words: Word puzzle** mobile application (also distributed as **Word Master**, hereinafter referred to as the "App"), developed by **Ranjit Pahan** ("we", "us", or "our"). 

We are committed to respecting and protecting your privacy. This policy explains what information the App collects, how it is used, how it is secured, and your rights when you play Master of Words.

---

## 1. Information We Collect

Master of Words is designed with an offline-first architecture. We do not require you to create an account, register an email address, or provide personal contact information to play. We do not operate proprietary external servers to collect, harvest, or sell your personal details. 

However, to deliver seamless puzzle gameplay, optional rewarded advertisements, app updates, and crash diagnostics, the App utilizes secure local device storage and industry-standard third-party Software Development Kits (SDKs).

### A. Locally Stored Data (On Your Device)
Your progress and game configurations are stored locally on your device:
* **Game Progress & Economy:** Current chapter, completed levels, level stars, discovered bonus words, gem balance, free hint balance, daily streak counter, and unlocked milestones.
* **Preferences & Settings:** Music volume, sound effects toggle, UI audio clicks, haptic feedback settings, and selected language.
* **Entitlement Status:** Purchase confirmation token for the permanent "Remove Ads" entitlement and Starter Bundle.
* **Security & Storage at Rest:** All sensitive game progress and player state are stored in a local NoSQL database encrypted at rest using **AES-256 encryption (`HiveAesCipher`)**. Cryptographic keys are generated and protected within your operating system's hardware-backed keystore (`Android Keystore` / `iOS Keychain` via `FlutterSecureStorage`).
* **Transmission:** We do not transmit, sync, or copy your local database save files to external personal servers.

### B. Local Notifications
The App utilizes device-level scheduling to deliver local reminders (e.g., reminding you when your Daily Reward is available or alerting you before your daily streak is lost):
* On devices running Android 13 (API level 33) or higher, the App requests the runtime `POST_NOTIFICATIONS` permission only after displaying an educational in-app explanation.
* These notifications are scheduled and evaluated **entirely on your device** using inexact background alarms; no device push tokens (FCM/APNs) or personal identifiers are transmitted to external push notification servers.
* If you disable notifications in device settings, the App automatically halts background alarm scheduling.

### C. Automatically Collected Data (Third-Party Services)
When your device connects to the internet, certified third-party service providers collect technical telemetry and advertising metrics:
* **Device & Network Identifiers:** Device model, hardware specifications, operating system version, mobile carrier, approximate IP-based location (country/city level), and resettable advertising identifiers (Google Advertising ID / AAID on Android, and Apple Identifier for Advertisers / IDFA on iOS if authorized).
* **App Activity & Gameplay Telemetry:** Anonymous event logs detailing puzzle interactions (e.g., `level_start`, `level_complete`, `hint_used`, `word_solved`, `gems_earned`, `rewarded_ad_request`, and session duration) collected via Firebase Analytics to help us refine puzzle difficulty curves.
* **Crash & Performance Diagnostics:** Anonymous stack traces, device memory state, crash event timestamps, and system diagnostics collected via Firebase Crashlytics to resolve stability bugs.
* **Advertising & Measurement Data:** Information regarding ad requests, impressions, click interactions, and video completions processed by Google AdMob to deliver ads and prevent fraudulent traffic.
* **Configuration Metadata:** App version number, bundle ID, and device language used by Firebase Remote Config to determine game balance parameters and verify mandatory update availability.

---

## 2. Third-Party Services & Integrations

The App integrates trusted third-party SDKs that process technical data under their respective privacy policies:

* **Google Mobile Ads (AdMob):** Serves banner ads, interstitial break ads, and optional rewarded video ads that keep the game free to play.
  * [Google Privacy Policy](https://policies.google.com/privacy)
  * [Google AdMob Information & Technologies](https://policies.google.com/technologies/ads)
* **Google Firebase (Analytics, Crashlytics & Remote Config):**
  * *Firebase Analytics:* Evaluates anonymized puzzle completion rates and feature engagement.
  * *Firebase Crashlytics:* Captures real-time crash logs to fix software errors.
  * *Firebase Remote Config:* Dynamically delivers balance adjustments (e.g., rewarded ad gem payouts, level pacing) and verifies minimum supported app versions without requiring constant store updates.
  * [Firebase Privacy and Security](https://firebase.google.com/support/privacy)
* **Google Play Games Services / Apple Game Center (Optional):** Provides cloud achievements and global leaderboards. If you sign in, authentication and score records are handled directly by Google or Apple; we do not store your passwords, gamer profiles, or social graphs on external servers.
  * [Google Play Games Terms](https://policies.google.com/privacy)
  * [Apple Privacy Policy](https://www.apple.com/legal/privacy/)
* **In-App Review Services:** Invokes native Google Play In-App Review or Apple StoreKit review dialogs directly via operating system APIs without collecting or storing player credentials.

---

## 3. In-App Purchases & Financial Data

Master of Words offers optional in-app purchases, including consumable Gem Packs, a Starter Bundle, and a permanent, non-consumable "Remove Ads" feature:
* All financial transactions are processed exclusively by **Google Play Billing** (on Android) or **Apple StoreKit** (on iOS).
* **We never collect, process, see, or store credit card numbers, banking details, or billing addresses.**
* We only receive an encrypted transaction receipt and product identifier from the platform store confirming payment validity so the App can credit your gems or remove ads.
* Non-consumable purchases ("Remove Ads") can be restored at any time via the in-game Settings menu.

---

## 4. How We Use Your Information

The data processed is used strictly for the following purposes:
1. **Core Gameplay Delivery:** Saving your puzzle progress, maintaining unlocked chapters, and crediting earned gems.
2. **Game Balancing & Optimization:** Analyzing aggregated completion rates and hint usage to tune puzzle difficulty and vocabulary lists.
3. **Monetization:** Displaying banner, interstitial, and rewarded ads to support ongoing development and serverless operations.
4. **App Maintenance & Remote Updates:** Dynamically verifying app versions via Firebase Remote Config to notify players of critical updates and improvements.
5. **Stability & Bug Elimination:** Analyzing crash diagnostics to resolve hardware-specific crashes across diverse Android and iOS devices.
6. **Security & Anti-Fraud:** Safeguarding ad networks against bot farms, click manipulation, and unauthorized game tampering.

---

## 5. Data Security & Encryption

We apply industry best practices to safeguard your data:
* **Encrypted in Transit:** All network communication between the App and third-party APIs (Google AdMob, Firebase, Google Play) is encrypted in transit using industry-standard **HTTPS / TLS (Transport Layer Security)** protocols.
* **Encrypted at Rest:** Local game saves, session history, and sensitive balance states are encrypted on your physical device using **AES-256 encryption (`HiveAesCipher`)**, with encryption keys managed by platform-native secure storage.

---

## 6. Your Rights, Consent & Data Deletion

Depending on your jurisdiction, you have legal rights regarding your personal information:

### A. European Privacy & Consent (GDPR / UK GDPR)
* **Google UMP Consent:** When launching the App in the European Economic Area (EEA) or the UK, a consent banner powered by the Google User Messaging Platform (UMP) allows you to accept or reject personalized advertising and vendor cookies.
* **In-App Revocation:** You can view, modify, or revoke your consent choices at any time directly in the game:
  * Open **Settings** (gear icon) > Tap **"GDPR Privacy Options"**.

### B. United States State Privacy Rights (California CCPA/CPRA, Virginia, Colorado, etc.)
Under the California Consumer Privacy Act (CCPA) and similar state laws:
* We **do not sell** your personal information for monetary compensation.
* To the extent that third-party ad networks use device identifiers to serve cross-context behavioral ads (which may be categorized as "sharing" or "targeted advertising"), you can opt out at any time using in-app privacy settings or device-level controls.

### C. Apple App Tracking Transparency (iOS ATT)
* On iOS 14.5 and newer, the App requests your permission via the native App Tracking Transparency (ATT) prompt before accessing your Identifier for Advertisers (IDFA).
* If you select "Ask App not to Track", AdMob will only serve non-personalized advertisements.
* You can adjust tracking permissions at any time via iOS *Settings* > *Privacy & Security* > *Tracking* > *Master of Words*.

### D. Device-Level Advertising Opt-Out
You can reset or opt out of interest-based advertising across all mobile apps via your operating system:
* **Android:** Open *Settings* > *Google* > *All services* > *Ads* > Tap *Delete advertising ID* or *Reset advertising ID*.
* **iOS:** Open *Settings* > *Privacy & Security* > *Apple Advertising* > Turn off *Personalized Ads*.

### E. Direct Data Deletion
Because we do not host personal player accounts on remote servers, you maintain complete, immediate control over your data:
* **In-App Reset:** You can instantly and permanently erase all saved progress, level stars, bonus words, and gem balances by opening the in-game **Settings** menu, scrolling to the **DANGER ZONE** section, and selecting **"Erase and Reset All Data"**.
* **App Uninstallation:** Uninstalling the App permanently removes all local databases, cached assets, and cryptographic keys from your device.

---

## 7. Children’s Privacy (COPPA & GDPR-K)

Master of Words is designed and intended for a general audience (ages 13 and older, or 16 and older in the EEA). We do not knowingly solicit or collect personally identifiable information from children under the age of 13.

If we discover that a child under 13 has provided us with personal information, we will take immediate measures to delete such data from our records. If you are a parent or guardian and believe your child has provided us with personal data, please contact us immediately.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect enhancements in game features, third-party SDK updates, or evolving legal obligations. Any revisions will be posted directly to this URL with an updated "Last Updated" date. We encourage you to review this policy periodically.

---

## 9. Contact Us

If you have any questions, suggestions, or concerns regarding this Privacy Policy or your data privacy, please contact:

* **Developer:** Ranjit Pahan  
* **Email:** pahan.ranjit.0201@gmail.com  
* **Hosted Policy URL:** https://ranjit-git.github.io/Privacy-Policy-for-Master-of-Words/
