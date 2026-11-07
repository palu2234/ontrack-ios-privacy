# OnTrack – Privacy Policy

**Last updated: November 7, 2026**

OnTrack ("the app") is a personal workout tracking app for iPhone and Android, developed by Michael Palummieri. This policy explains what data the app accesses, how it is used, and your rights as a user. It covers both OnTrack for iPhone (with its Apple Watch app) and OnTrack for Android.

---

## Data We Collect

OnTrack does not collect, transmit, or store any personal data on our servers. The app has no backend, no user accounts, no advertising, and no third-party analytics. We never receive your workouts, measurements, photos, or health data. The only information we receive is what you choose to email us, for example a problem report or feedback (see "Feedback, support and crash reports").

All data you enter — workouts, sets, exercises, templates, plans, notes, body measurements, progress photos, and preferences — is stored on your device. It leaves your device only when you choose to back it up or share it, as described below:

- **iPhone:** in your personal iCloud account, if you enable it.
- **Android:** in your own Google account, through Android's device backup and, if you turn it on, OnTrack's Google Drive backup.

---

## Apple Health (HealthKit) — iPhone

If you grant permission, OnTrack reads and writes data to Apple Health. Specifically:

- **Reads:** Body weight and body fat percentage, to display your measurements in the app.
- **Writes:** Workout sessions, active energy burned, heart rate (from Apple Watch), body weight, and body fat percentage.

HealthKit data is used solely to provide app functionality. It is never shared with third parties, never used for advertising, and never sent to any server.

You can revoke HealthKit access at any time in the iOS Settings app under Privacy & Security → Health → OnTrack.

---

## Health Connect — Android

Health Connect is optional. If you turn on Health Connect sync and grant permission, OnTrack reads and writes the following data types, each for a feature you can see in the app:

| Data type | Read | Write | What it's for |
|---|---|---|---|
| Exercise sessions | ✓ | ✓ | Writes each workout you finish in OnTrack. Reads workouts other apps logged at the same time, to tell whether your watch recorded the same workout. |
| Heart rate | ✓ | ✓ | Writes the heart rate a Bluetooth monitor recorded during a workout. Reads heart rate your watch recorded, to draw the heart-rate graph for that workout. |
| Weight | ✓ | ✓ | Writes weight you log in OnTrack. Reads weight from other apps (for example a smart scale) into your body-measurement history and charts. |
| Body fat | ✓ | ✓ | Same as weight. |
| Active calories burned | ✓ | | Optional. Shows the calories your watch measured for a workout, only when your watch logged that same workout. OnTrack never estimates calories. |

How OnTrack handles Health Connect data:

- Weight and body fat read from Health Connect are saved in OnTrack's on-device database, so they appear in your measurement history. Watch-measured calories are saved with the workout they belong to. Heart-rate readings from Health Connect are read when you open a workout, to draw its graph, and are not stored.
- Health Connect data is used only to provide the features above. It is never sold, never used for advertising, never used for credit or lending decisions, and never sent to us or to any third party.
- Health Connect data leaves your device only inside a backup or export that you choose to make (see "Backups, exports and sharing"), where it is stored in your own account or sent where you choose.
- To stop sync, turn off Health Connect in OnTrack's Settings. To remove access, open Health Connect → App permissions → OnTrack. Data OnTrack wrote to Health Connect stays there until you delete it in Health Connect.

---

## Bluetooth heart-rate monitors — Android

If you pair a Bluetooth heart-rate monitor (a chest strap, or a watch broadcasting heart rate), OnTrack connects to the monitor you pick and reads only its heart-rate measurements during a workout or circuit. Those readings are saved with the workout on your device (for its heart-rate graph and average), and, if Health Connect sync is on, written to Health Connect. OnTrack remembers the monitor's Bluetooth name and address on your device so it can reconnect.

On Android 12 and newer, OnTrack asks for the Nearby devices permission and declares that it does not use Bluetooth scans to determine your location. On Android 11 and older, Android requires the location permission for any app that scans for Bluetooth devices. OnTrack asks for it only to find your monitor and never reads, stores, or shares your location.

While a workout or circuit records heart rate, Android shows a notification for OnTrack's workout service, which keeps recording when the screen is off.

---

## Photos, videos and camera

Progress photos you take or choose are stored in OnTrack's private storage on your device. Photos are taken with your device's camera app, and photos or videos you attach are chosen through the system picker, so OnTrack never has access to the rest of your photo library. Videos attached to a set stay in your library; OnTrack keeps only a link to them.

---

## iCloud Backup — iPhone

If you have iCloud Drive enabled, OnTrack may save an automatic backup of your data to your personal iCloud Drive. This backup is stored in your own iCloud account and is governed by Apple's iCloud Terms and Privacy Policy. OnTrack has no access to this data outside your devices.

---

## Google backups — Android

- **Android device backup.** If backup is on for your device, Android backs up OnTrack's data (not progress photos) to your Google account, and restores it when you set up a new Android phone. This is handled by Android and governed by Google's Privacy Policy.
- **Google Drive backup (optional).** If you turn on "Back up to Google Drive" in Settings, you sign in with your Google account and allow OnTrack to use files it creates in your Drive. OnTrack then saves one backup file, My Drive › OnTrack › ontrack-backup.json, each time you leave the app. You can open that file on an iPhone to move your data to OnTrack for iPhone. OnTrack can see only the files it created, never the rest of your Drive. The file is stored in your own Google account, governed by Google's Terms and Privacy Policy, and sent over an encrypted (HTTPS) connection directly from your phone to Google. We never receive it. Turn it off in Settings; remove OnTrack's access in your Google Account under Security → Your connections to third-party apps & services.

---

## Apple Watch

If you use the OnTrack Apple Watch app, your active workout data (sets, reps, weight) is synced directly between your iPhone and Apple Watch using Apple's WatchConnectivity framework. No data passes through external servers.

---

## Backups, exports and sharing

Backups and exported files (CSV or OnTrack backup files) contain all your OnTrack data, including measurements brought in from Apple Health or Health Connect. Files you export, and workouts you share with friends, go only to the app or person you choose in the share sheet. A shared file includes the display name you set in Settings, so the recipient can see who sent it.

---

## Feedback, support and crash reports — Android

OnTrack for Android lets you report a problem, request a feature, share feedback, or ask a question from Settings → Feedback & support. OnTrack has no server, so this works through email:

- OnTrack opens your own email app with a message to support@corefirststudios.com already filled in. Nothing is sent until you press Send in your email app, and you can read and edit everything before you do.
- You can choose to include **app and device details**: the app version, Android version, phone model, language, time zone, screen size, your OnTrack settings (such as units, whether Pro is unlocked, and whether Health Connect, Google Drive backup, a heart-rate monitor, or Garmin saving are turned on, including the name of your saved heart-rate monitor), and counts from your data (such as how many workouts, templates, and exercises you have, or how many sets use RPE or supersets). They are counts and settings only. Workout names, exercise names, notes, weights, measurements, photos, and health data are never included.
- If OnTrack crashes, the technical details of that crash (an error description and where in the app's code it happened) are kept in OnTrack's private storage on your phone. The next time you open the app, OnTrack asks once whether you'd like to send a problem report. The details are included only if you choose to send them, and they're never sent automatically. A newer crash replaces the older one, and deleting the app or clearing its storage removes them.

When you email us, we receive your email address, your message, and whatever details you chose to include. We use them only to answer you and to fix and improve OnTrack. We never sell them, never use them for advertising, and never share them with anyone else.

---

## Usage stats (optional) — Android

"Share usage stats" in Settings → Feedback & support is **off unless you turn it on**. While it's on, OnTrack keeps simple counts on your phone: how many times you open the app, on how many days you use it, how often you visit each screen, how often you use tools such as the timer, plate calculator, and guided circuits, and which OnTrack Pro features you tap on while they're locked.

- The counts never include workout content, names, notes, weights, health data, or the time of individual visits.
- They stay on your phone. They're sent to us only when you choose to send them, either with "Send usage report" or by including them in feedback, using the same email process described above, so you can read them first.
- They're kept apart from your other data and are not part of Android device backup or device-to-device transfer.
- Turning "Share usage stats" off immediately erases every count kept so far.

---

## Third-Party Services

OnTrack does not integrate any third-party analytics, advertising SDKs, crash reporting services, or social media frameworks. The optional usage stats and crash details described above are kept by OnTrack itself on your phone and reach us only by an email you choose to send. Separately, if you allow it in your device settings, Apple or Google may share anonymous app crash reports with developers. That's handled by Apple or Google under their own privacy policies. The Android app uses Google services only for the optional features above: Health Connect, and Google sign-in with the Google Drive API for Drive backup.

---

## Data retention and deletion

Your data stays on your device until you delete it. You can:

- Delete any workout, measurement, or photo in the app.
- Erase everything on a device by deleting the app (on Android you can also clear its storage in Settings → Apps → OnTrack).
- Delete backups from iCloud Drive or Google Drive, and remove OnTrack's access as described above.
- Delete data OnTrack wrote to Apple Health or Health Connect in those apps.

Because we never receive your app data, we have nothing stored about you to delete. If you've emailed us (for example, a problem report, feedback, or a usage report), we keep that email only as long as we need it to help you and improve OnTrack. Ask us at any time and we'll delete it. Contact us if you have any question about your data.

---

## Security

Your data is kept in the app's private storage on your device, protected by your device's security. Backups to Google Drive are sent over encrypted HTTPS connections.

---

## Children's Privacy

OnTrack is not directed at children and does not knowingly collect any information from children under the age of 13.

---

## Changes to This Policy

If this policy changes materially, the "Last updated" date above will be revised. Continued use of the app after changes constitutes acceptance of the revised policy.

---

## Contact

If you have questions about this privacy policy, contact:

Michael Palummieri
support@corefirststudios.com
