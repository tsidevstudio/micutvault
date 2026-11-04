# MicutVault Troubleshooting

This page covers common user-facing issues in the current MicutVault Production release.

For additional help, contact:

support@tsidevstudio.com

Official MicutVault page:

https://tsidevstudio.com/apps/micutvault

## I cannot unlock the vault

If MicutVault does not unlock as expected:

- Confirm that you are entering the correct Primary PIN.
- The Primary PIN must contain between 6 and 12 digits.
- If biometric unlock is enabled, confirm that biometric authentication is still available on the device.
- If Android security settings or enrolled biometrics were changed, restart MicutVault and authenticate again with the Primary PIN.
- If lockout protection was triggered after repeated incorrect PIN attempts, wait until the configured lockout period has expired.

Do not uninstall the app as a troubleshooting step if you have private content that has not been backed up.

## Biometric unlock is unavailable

Biometric access depends on the Android device and its supported secure authentication methods.

Check that:

- biometric authentication is configured in Android
- the device supports an eligible biometric method
- biometric access is enabled in MicutVault
- the Primary PIN still works

Changes to Android biometric enrollment or device security settings may require authentication with the Primary PIN again.

## A disguise mode does not appear as expected

MicutVault supports nine disguise modes:

- Calculator
- Notes
- Books
- Files
- Calendar
- Clock
- Tasks
- Scanner
- Recorder

Behavior and launcher appearance can vary depending on Android version, device manufacturer and launcher implementation.

If a disguise change does not appear immediately:

- return to the home screen
- allow the launcher to refresh
- restart the launcher or device if necessary
- reopen MicutVault and confirm the selected disguise mode

Do not repeatedly uninstall and reinstall the app to refresh a disguise.

## Calculator mode does not open the vault

Calculator mode also functions as a normal calculator.

To attempt vault access:

1. Enter your valid 6–12 digit Primary PIN as a plain number.
2. Press `=`.

Normal mathematical expressions continue to behave as calculator input.

If access is temporarily blocked because of repeated incorrect PIN attempts, wait for the configured lockout period to expire.

## Intruder detection does not work

Intruder detection is optional.

Confirm that:

- Intruder Detection is enabled in MicutVault
- the required Android camera permission has been granted
- the device has an available front-facing camera
- Android has not removed or restricted the permission

Intruder detection is associated with repeated failed PIN attempts rather than normal calculator use.

Device behavior may vary depending on Android version and manufacturer restrictions.

## Auto-lock activates sooner than expected

MicutVault supports configurable inactivity auto-lock.

Available options include:

- 1 minute
- 3 minutes
- 5 minutes

Check the selected timeout in MicutVault settings.

Backgrounding the app or device security behavior may also cause the vault to require authentication again.

## I deleted something accidentally

Deleted private content may remain available in the encrypted Trash for up to 30 days.

Open the Trash and restore the content if it has not yet been permanently removed.

Content that has already passed the Trash retention period or has been permanently deleted cannot be restored through Trash.

## Backup or restore problems

MicutVault supports encrypted backup and restore.

If a backup cannot be restored:

- confirm that you selected the correct MicutVault backup file
- confirm that the required recovery credentials are correct
- make sure the backup file has not been renamed, modified or corrupted
- ensure sufficient free storage is available on the device

Keep backup files and recovery credentials in a safe location.

Do not modify the contents of a MicutVault backup file manually.

## Imported content does not appear

If recently imported content is not visible:

- confirm that the import completed successfully
- check the appropriate Photos, Videos, Audio or Notes section
- verify available device storage
- reopen the relevant vault section

If the problem persists, contact support before deleting or re-importing important content.

## The app does not behave correctly after an Android update

Android system or launcher updates can occasionally change permission, biometric or launcher behavior.

Try:

1. Restarting the device.
2. Opening MicutVault normally.
3. Authenticating with the Primary PIN.
4. Checking biometric and camera permissions if those optional features are used.
5. Confirming the selected disguise mode.

If the issue continues, contact support with:

- Android version
- device manufacturer and model
- MicutVault version
- a short description of the issue

Do not include your PIN, recovery credentials or private vault content in a support message.

## Official links

- Google Play: https://play.google.com/store/apps/details?id=com.tsi.micutvault
- MicutVault: https://tsidevstudio.com/apps/micutvault
- Privacy Policy: https://tsidevstudio.com/privacy/micutvault
- TSI Dev Studio: https://tsidevstudio.com

## Support

support@tsidevstudio.com
