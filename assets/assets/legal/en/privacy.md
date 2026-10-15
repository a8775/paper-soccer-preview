# Privacy Policy

*“Piłkarzyki na kartce” (Paper Soccer) app · version 1.0 · effective from [EFFECTIVE DATE]*

> **In short.** Playing against the computer happens on your phone, even offline. Only your profile, nickname, points, statistics, match history and interrupted match go to the cloud (Google Firebase) – so that leaderboards and sync work. Your nickname and points are public on the leaderboard. Personalized ads, usage statistics and crash reports are turned on only with your consent. You can delete your account and all data with one button in Settings.

## 1. Controller and contact

The controller of your personal data is [FULL NAME / COMPANY NAME], [ADDRESS] (“we”, “us”). For any data protection matters, write to [E-MAIL ADDRESS]. We have not appointed a data protection officer.

This policy covers the “Piłkarzyki na kartce” (Paper Soccer) mobile app for Android and iOS. Capitalized terms have the meaning given in the [Terms of Use](terms.md).

## 2. What data we process, why and on what basis

Legal bases are under the GDPR: Article 6(1)(a) (consent), (b) (performance of the agreement – the Terms), (c) (legal obligation) and (f) (our legitimate interest).

### 2.1. Account and sign-in (Firebase Authentication)

- **Data:** the Account identifier (UID); nothing else for a guest account. When signing in with Apple or Google, also your identifier with that service and the e-mail address Apple or Google shares with us (Apple lets you hide your real address), and which sign-in method you use. We never receive passwords.
- **Purpose:** creating and maintaining your Account, attaching your results to it, linking a guest account to Apple or Google, restoring the Account on a new device.
- **Basis:** performance of the agreement (b).

### 2.2. Profile, statistics, history and sync (Cloud Firestore)

- **Profile data:** nickname, pen color, sign-in methods, creation and update dates, points (total and current week), statistics (played, won, lost, how you won, own goals, resignations, streaks, number of segments and bounces, total play time, results per level), achievements with the dates you earned them.
- **Match history:** for each match – dates and duration, App and engine version, settings (level, field, who starts, clock, move preview, undo), the computer’s random seed, the move record, the result and its reason, points, number of hints and undos.
- **Interrupted match:** the state of a match in progress (settings, moves, ball position, time, hints and undos left) – saved when you pause, leave a match or the App goes to the background.
- **Purpose:** profile, statistics, achievements, match replays, resuming a match and syncing between devices.
- **Basis:** performance of the agreement (b).

### 2.3. Nickname and public leaderboard

- **Data:** nickname, pen color, points and rank on the world and weekly leaderboards. **Other Users can see this data.** The nickname reservation (nickname → UID) is public so that nobody else can take the same nickname.
- **Moderation:** nicknames are checked by an automatic word filter; if reported, we may also review them manually.
- **Purpose and basis:** running the leaderboard – performance of the agreement (b); moderating nicknames and protecting other Users – our legitimate interest (f).

### 2.4. Game Center and Google Play Games

- **Data:** your score and earned achievements, sent to Game Center (iOS) or Google Play Games (Android) if you are signed in to them.
- **Purpose and basis:** friends leaderboard and platform achievements – performance of the agreement (b).
- Apple and Google process this data as independent controllers under their own privacy policies. You control your profile’s visibility to friends in Game Center or Play Games.

### 2.5. Fraud prevention and security (Firebase App Check, security rules)

- **Data:** tokens confirming that a request comes from the genuine App on a real device (Google Play Integrity on Android, App Attest / DeviceCheck on iOS), IP address and basic technical information about the request.
- **Purpose:** protecting the leaderboard from forged results (including a cap on points growth), protecting data and infrastructure from abuse.
- **Basis:** our legitimate interest (f) – a fair leaderboard and a secure service.

### 2.6. Remote configuration (Firebase Remote Config)

- **Data:** Firebase installation ID, App and OS version, device language and country.
- **Purpose:** delivering settings without an App update, e.g. the frequency of full-screen ads and the balance of computer levels.
- **Basis:** performance of the agreement (b) and our legitimate interest (f).

### 2.7. Usage statistics (Google Analytics for Firebase) – only with consent

- **Data:** App instance ID, in-app events (e.g. screens opened, match start and result, computer level, use of hints), device model, OS and App version, language, approximate country or region derived from the IP address. We do not link this data to your nickname or e-mail address.
- **Purpose:** understanding how the game is used and tuning the computer levels.
- **Basis:** consent (a), given with the “Usage statistics” switch.

### 2.8. Crash reports (Firebase Crashlytics) – only with consent

- **Data:** error trace (stack trace), time of the crash, device model, OS and App version, free memory, Crashlytics installation ID.
- **Purpose:** finding and fixing bugs.
- **Basis:** consent (a), given with the “Crash reports” switch.

### 2.9. Ads (Google AdMob)

Described in [section 4](#4-ads-and-your-consents).

### 2.10. Contact, bug reports and complaints

- **Data:** e-mail address, message content and anything you choose to include (e.g. nickname, device model, App version).
- **Purpose and basis:** replying to and handling your message – our legitimate interest (f); handling complaints and data protection requests – legal obligation (c).

## 3. Data stored only on your phone

The App stores on your device: settings (game, sound and vibration, theme, color-blind mode, language), your consent choices, age confirmation, an autosave of the current match (after every move), a local history for replays, a match counter used to show full-screen ads less often and which cards with our other games you have hidden. This data stays on your phone, except for the saves described in section 2.2. You can delete it by uninstalling the App or clearing its data in system settings.

The App does not ask for access to GPS location, contacts, photos, camera or microphone. Vibration and sounds work locally.

## 4. Ads and your consents

The App is free thanks to Google AdMob ads: banners in the menu, leaderboard and profile (never on the board), full-screen ads after a match (at most every second match, not in your first matches and not after the tutorial) and optional rewarded ads (a hint or 3 undos).

In the menu and in Settings we also recommend our other games. It is a plain link to the app store – no data is shared with anyone, and you can hide the card in the menu.

- **Data processed by Google and its ad partners:** the device advertising ID (Android Advertising ID / IDFA on iOS – only if you allow it), IP address, approximate location derived from it, information about the device, OS and App, information about ad impressions and interactions.
- **Personalized ads** are shown only if you turn on “Ads tailored to me”, consent in Google’s consent form (UMP) and, on iPhone, allow tracking in the system prompt (App Tracking Transparency). Basis: consent (Article 6(1)(a) GDPR and Article 399 of the Polish Electronic Communications Law).
- **Non-personalized ads** are shown if you do not consent to personalized ads or do not confirm that you are at least 16. They are not based on your history, but Google may use identifiers and the IP address for frequency capping, fraud detection and ad measurement – within the choices you made in the consent form. Basis: our legitimate interest in funding a free App (f), and consent where required for storing or reading information on the device.
- **The list of ad partners** is available in Google’s consent form, opened from the “Consent and privacy” screen (the “Ad partners” link). How Google uses data: [policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites).

### How to change or withdraw consent

- In the App: **Settings → Privacy and ads → Ads and analytics consent**. Withdrawing consent does not affect the lawfulness of processing before withdrawal.
- iPhone: system Settings → Privacy & Security → Tracking.
- Android: system Settings → Google → Ads (reset or delete the advertising ID).

## 5. Recipients

We do not sell your data. We share it only with:

- **Google Ireland Limited** (Ireland) and **Google LLC** (USA) – Firebase (Authentication, Cloud Firestore, App Check, Remote Config, Analytics, Crashlytics), Sign in with Google, Google Play Games, AdMob and the UMP consent form. For Firebase, Google acts as our processor; for ads, sign-in and Play Games, also as an independent controller. [Google Privacy Policy](https://policies.google.com/privacy).
- **Apple Distribution International Ltd.** (Ireland) and **Apple Inc.** (USA) – Sign in with Apple, Game Center, App Attest – as an independent controller. [Apple Privacy Policy](https://www.apple.com/legal/privacy/).
- **Google’s ad partners** – within your consents (section 4).
- **Other Users** – nickname, color and points on the leaderboard.
- **Public authorities** – where required by law.

## 6. Transfers outside the EEA

Google LLC and Apple Inc. may process data in the USA and other countries outside the European Economic Area. Transfers are based on the European Commission’s adequacy decision of 10 July 2023 (EU-US Data Privacy Framework – both companies are certified) and, additionally, on standard contractual clauses approved by the Commission. You can get a copy of the safeguards by writing to us.

## 7. How long we keep data

| Data | Period |
|---|---|
| Account, profile, nickname, points, statistics, achievements | Until the Account is deleted. Guest accounts unused for [24 MONTHS] are deleted automatically. |
| Match history in the cloud | 12 months after the match ends (automatic deletion), or earlier when the Account is deleted. |
| Interrupted match in the cloud | Until the match is finished or abandoned, or the Account is deleted. |
| Usage statistics (Analytics) | User-level data – 2 months; after that only aggregated reports without identifiers. |
| Crash reports (Crashlytics) | 90 days. |
| Advertising data | According to the rules of Google and its ad partners (listed in the consent form). |
| Correspondence and complaints | Until the matter is closed, then until any claims become time-barred. |
| Data on your phone | Until you uninstall the App or clear its data. |

## 8. Account and data deletion {#account-deletion}

**In the App:** Settings → **Delete account and all data** → confirm. The App immediately deletes your match history, interrupted match, profile with statistics and points, nickname reservation and, finally, the Account itself in Firebase Authentication. Your nickname disappears from the leaderboard.

**Without the App:** e-mail [E-MAIL ADDRESS] with the subject “Account deletion”, stating your nickname and sign-in method (guest, Apple, Google). We may ask for information confirming the Account is yours. We will delete the data within 30 days and confirm by e-mail.

Deleting the Account does not delete data in Game Center and Google Play Games (delete it in those services’ settings) or data on your phone (uninstall the App). Google’s service backups are overwritten within their standard cycles. Data we must keep by law (e.g. complaint correspondence) is kept only for the required period.

## 9. Your rights

You have the right to:

- access your data and get a copy,
- rectify your data (you can change your nickname in Settings),
- erasure (section 8),
- restriction of processing,
- data portability for data processed on the basis of the agreement or consent,
- object to processing based on our legitimate interest,
- withdraw consent at any time (section 4),
- lodge a complaint with the President of the Polish Personal Data Protection Office (ul. Stawki 2, 00-193 Warsaw, [uodo.gov.pl](https://uodo.gov.pl/en)) or the supervisory authority in your country of residence.

To exercise your rights, write to the address in section 1. We will reply within one month. Providing data is voluntary, but without a UID and profile data we cannot maintain an Account or leaderboard – you can still play against the computer offline.

## 10. Children and teenagers

On the “Consent and privacy” screen we ask whether you are at least 16. If you do not confirm this, we show only non-personalized ads and do not turn on usage statistics or crash reports, because people under 16 cannot consent to such processing themselves (Article 8 GDPR). The App is not directed at children under 13. A parent or guardian who believes a child has given us data can write to us and we will delete it.

## 11. Security and profiling

- Connections to our servers are encrypted (TLS). Database security rules let each User read and change only their own data (except the public leaderboard and nickname reservations), and App Check blocks requests not coming from the genuine App.
- We do not make decisions about you based solely on automated processing that produce legal effects or similarly significantly affect you. Automatic point caps and the nickname filter keep the leaderboard fair – if you disagree with their outcome, write to us and a human will review it.
- Personalized ads involve profiling by Google and its ad partners – only with your consent.
- The computer you play against is an algorithm running on your phone; it does not analyze your personal data.

## 12. Changes to this policy

We update this policy when the App’s features, the services we use or the law change. We will tell you about significant changes in the App, and if a change requires new consent, we will ask for it again.
