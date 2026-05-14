# Privacy Policy

**Last updated:** May 14, 2026

This Privacy Policy describes how "FlipDrop" ("the App", "we", "our") collects, uses, and shares information when you use our mobile application.

## Information We Collect

### Information You Provide
- **Player name (optional):** You may enter a display name in Settings. It is stored on your device and is also **submitted to our online leaderboard** (see "Online Leaderboard" below), where it is visible to other players. You can change or clear it at any time from Settings.

### Information Collected Automatically
- **Device motion (accelerometer):** The App reads device orientation in real time to change the in-game gravity when you rotate your phone. This data is processed only on-device and is never stored or transmitted.
- **Install identifier:** On first launch the App generates a random identifier (e.g. "anon-…"). It is not linked to your real identity and is used as your key in the online leaderboard when you are not signed in to Google Play Games.

### Information from Google Play Games (optional)
If you choose to sign in with Google Play Games from Settings, the App receives your **Google Play Games player ID and display name** and uses them to identify your entries on the online leaderboard across devices. Sign-in is optional — the App is fully playable without it.

## Online Leaderboard

FlipDrop has a global weekly leaderboard. When a game session ends with a score, the App submits the following to a Google Firebase Realtime Database:

- Your display name and/or Google Play Games name
- Your Google Play Games player ID, or your random install identifier if you are not signed in
- Score, highest combo, highest tile value, and session duration
- A timestamp and the leaderboard week

The App also downloads the current weekly leaderboard to show it in the in-game Hall of Fame. **Leaderboard entries are visible to other players.** Please do not enter a display name you would not want shown publicly.

## Third-Party Services

### Firebase Realtime Database (Google)
The online leaderboard is hosted on Google Firebase. The leaderboard data described above is stored on Google's servers. See [Google's Privacy Policy](https://policies.google.com/privacy) and [Firebase Privacy and Security](https://firebase.google.com/support/privacy).

### Google Play Games Services
Optional sign-in that gives the App a stable cross-device identity for the leaderboard. See [Google's Privacy Policy](https://policies.google.com/privacy).

### Google AdMob
The App displays advertisements provided by Google AdMob (rewarded ads tied to power-ups and the "continue after game over" feature, plus an interstitial when a session ends). Google may collect and process certain information including:
- Device identifiers (advertising ID)
- IP address
- General location (country/region level)
- App usage data

Users who purchase the "Remove Ads" in-app product no longer see ads after purchase.

For more information, see [Google's Privacy Policy](https://policies.google.com/privacy).

### Google Play Billing
The in-app purchase "Remove Ads" is processed by Google Play Billing. We do not collect or receive your payment details — Google Play handles the transaction and only reports the purchase status back to the App.

For more information, see [Google Play Privacy Policy](https://play.google.com/about/play-terms/).

## Information We Do NOT Collect
- We do not require account creation or login (Google Play Games sign-in is optional)
- We do not collect email addresses, phone numbers, or real names
- We do not collect precise location data
- We do not access contacts, photos, microphone, or camera
- We do not use analytics, crash-reporting, or attribution SDKs
- We do not track users across other apps or websites
- We do not sell any user data to third parties

## Data Storage

### On your device
Gameplay data is stored on your device via Android `SharedPreferences`:
- Best score and saved game-in-progress snapshot (so you can resume)
- Selected language and sound on/off preference
- "Remove ads" purchase status
- Your chosen display name, your random install identifier, and — if you signed in — your Google Play Games ID and name

Uninstalling the App removes all of this local data.

### On our servers
Leaderboard entries (see "Online Leaderboard") are stored on Google Firebase. A new leaderboard is started each week. Uninstalling the App stops any further submissions but does not automatically remove entries you have already submitted — to request removal of your leaderboard data, contact us at the email below.

## Permissions
The App declares the following Android permissions:

- **`INTERNET`** — required to fetch ads from Google AdMob and to submit and read the online leaderboard.
- **`com.google.android.gms.permission.AD_ID`** — gives AdMob access to the Android advertising identifier (revocable from your device settings).
- **`com.android.vending.BILLING`** — required to offer the "Remove Ads" in-app purchase via Google Play Billing.

No other runtime permissions are requested.

## Children's Privacy
The App is suitable for general audiences. We do not knowingly collect personal information from children under 13. The only user-provided data is an optional display name; because it is shown on the public leaderboard, we recommend not using a real name. If you believe a child has provided personal information, contact us and we will remove it.

## Your Rights
- You can delete all local data (scores, preferences, saved game, display name, identifiers, purchase status cache) by clearing the app's storage from Android Settings or by uninstalling the App.
- You can change or remove your display name at any time from Settings.
- You can request removal of your online leaderboard data by contacting us at the email below.
- You can reset your advertising ID through your device settings.
- You can opt out of personalized ads through your device settings.

## Changes to This Policy
We may update this Privacy Policy from time to time. We will notify users of any material changes by updating the "Last updated" date at the top of this policy.

## Contact Us
If you have questions about this Privacy Policy, please contact us at:

**Email:** t.ganaj@gmail.com

---

This app is developed by Ganaj and is available on Google Play.
