# MoneyMate Privacy Policy

**Effective date:** October 31, 2026  
**App:** MoneyMate  
**Developer:** BlueMangoTreeHouse  
**Contact:** overflownode@gmail.com

This policy explains what information the MoneyMate mobile app handles, how it is used, where it is stored, and the choices you have. It applies to the MoneyMate app on Android and iOS, including the version distributed through Google Play.

## Summary

- Your finance data is stored on your device. MoneyMate does not operate a server, and the developer does not receive or have access to your finance data.
- Signing in with Google is optional. You can use every budgeting and tracking feature without an account.
- If you turn on Google Drive backup, an encrypted, compressed copy of your data is saved in a hidden MoneyMate folder in **your own** Google Drive. MoneyMate cannot see any other files in your Drive.
- MoneyMate does not sell your data, does not show ads, and does not include advertising, analytics, or tracking SDKs.

## Information stored on your device

MoneyMate stores the information you enter in a database on your device:

- Transactions: amount, type (income or expense), category, payment method, note, and date.
- Categories: name, icon, color, order, and visibility.
- Monthly and category budgets.
- App preferences, such as whether you have completed onboarding.

This information is used only to provide the app's tracking, budgeting, and reporting features. It stays on your device unless you turn on Google Drive backup.

If you sign in with Google, MoneyMate also stores your basic Google profile details (listed below) and the backup status (for example, the time of the last backup) in the device's secure storage. Sign-in authorization is managed by Google's sign-in service on your device.

## Google Sign-In (optional)

You can choose to sign in with your Google account from **Settings** or **Profile**. MoneyMate never receives your Google password.

When you sign in, MoneyMate receives:

- your name,
- your email address,
- your profile photo (as a link provided by Google), and
- your Google account identifier,

and, with your permission, authorization to access the MoneyMate app folder in your Google Drive.

This information is used to:

- show who is signed in on the Profile and Settings screens,
- make sure a backup is restored only into the Google account that created it, and
- create, update, and restore your MoneyMate backup in your Google Drive.

The account identifier is also used on your device to generate the key that encrypts and decrypts your backup.

## Google Drive backup and restore (optional)

When you are signed in, MoneyMate requests only the Google Drive **app data** permission (`https://www.googleapis.com/auth/drive.appdata`). This permission gives MoneyMate access to a private folder that only MoneyMate can use. MoneyMate **cannot** see, read, or change your other Google Drive files, and the backup does not appear in your normal Drive file list.

**What is backed up:** one file, `moneymate_backup.json`, containing your transactions, categories, category budgets, monthly budgets, the onboarding preference, the backup date, and the email address of the Google account that owns the backup.

**When backups happen:**

- automatically, a few seconds after you add, edit, or delete data, and
- when you tap **Backup Now**.

If your device is offline, the backup waits and runs when your connection returns.

**Restoring:** MoneyMate restores a backup only after you confirm. A restore replaces the finance data on the device with the data in the backup. MoneyMate checks the backup before using it. If the backup is invalid, or the restore fails, your existing data is kept.

**How the backup is protected:**

- Before upload, the backup is compressed and encrypted on your device with AES-256-GCM.
- It is sent over an encrypted (HTTPS) connection directly from your device to Google.
- The encryption key is generated on your device from a value built into the app and your Google account identifier. This lets a backup be restored on another device signed in to the same Google account without a separate password.
- The encryption protects the file's contents if it is accessed outside MoneyMate, and it detects tampering or damage.
- It is not a substitute for keeping your Google account secure.

Your backup is stored by Google under the [Google Terms of Service](https://policies.google.com/terms) and [Google Privacy Policy](https://policies.google.com/privacy).

## Google API Services User Data Policy

MoneyMate's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Information received from Google is:

- used only to provide the sign-in, backup, and restore features described above;
- not sold;
- not used for advertising;
- not used to build user profiles;
- not used to train artificial intelligence or machine learning models; and
- not transferred to anyone else except as necessary to provide these features, to comply with law, or as part of a merger or acquisition with notice to you.

The developer does not read your Google data.

## Sharing

MoneyMate does not sell, rent, or trade personal information. Information leaves your device only when you use Google Sign-In or Google Drive backup. In that case it is exchanged directly between your device and Google to provide the feature you chose.

Information may be disclosed if required by law. The developer does not hold copies of your data.

## Device permissions

MoneyMate uses internet access and network-state access only to communicate with Google for sign-in and backup, and to retry backups when your connection returns. The app does not request access to your contacts, location, camera, microphone, or files.

## Retention and deletion

- **Data on your device** stays until you delete it in the app or uninstall the app. Uninstalling removes it from the device.
- **Signing out** (Settings → Google Account → Sign out) stops future backups and removes your Google name and photo from the app. Your email address and the time of your last backup stay in the app's secure storage, so the correct backup is used if you sign in again. Your finance data stays on the device, and your Drive backup is kept. Uninstalling the app removes everything stored on the device.
- **Your Drive backup** stays in your Google Drive until you delete it. To delete it:
  1. Open [Google Drive](https://drive.google.com) on the web.
  2. Go to **Settings → Manage apps**.
  3. Find **MoneyMate**, then select **Options → Delete hidden app data**.
- **Revoking access:** you can remove MoneyMate's access to your Google account at any time at [myaccount.google.com/connections](https://myaccount.google.com/connections). Revoking access does not delete a backup that already exists.
- **Device backups:** your device's own backup service (for example, Android backup) may separately back up app data according to your device and account settings.

## Security

MoneyMate uses:

- the protections of your device's operating system,
- secure storage for account and backup status, and
- encrypted connections and on-device encryption for cloud backups.

No method of storage or transmission is completely secure. Protect your device with a screen lock and your Google account with a strong password and 2-Step Verification.

## Children's privacy

MoneyMate is a personal finance tool and is not directed to children under 13. MoneyMate does not knowingly collect personal information from children under 13. If you believe a child has provided information through MoneyMate, contact us at the address below.

## Your choices and rights

You choose:

- what information to enter,
- whether to sign in with Google, and
- whether to keep a Drive backup.

You can delete local data, sign out, delete your Drive backup, or revoke access as described above.

Depending on where you live, you may have rights to access, correct, delete, or restrict the processing of your personal information. Because the developer does not hold your data, most requests can be completed directly with the controls above. You can also contact us for help.

## International processing

If you use Google Sign-In or Drive backup, Google may process and store your information in countries where Google or its service providers operate, as described in Google's privacy policy.

## Changes to this policy

We will update this policy when MoneyMate's features or data practices change, for example before introducing advertising or any new data collection. The updated policy will be published at https://bluemangotreehouse.github.io/moneymate-privacy-policy/ with a new effective date. Where required, we will also notify you in the app.

## Contact

For questions or privacy requests, contact **overflownode@gmail.com**.
