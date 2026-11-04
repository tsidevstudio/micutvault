# MicutVault Privacy Features

This page describes public, user-visible privacy and security features available in MicutVault.

Implementation details that could weaken security or make protective mechanisms easier to reproduce or bypass are intentionally not documented publicly.

## Local-first design

MicutVault is designed around local control of private content.

The current Production release has:

- No account requirement
- No ads
- No analytics
- No mandatory cloud storage
- No subscription

Private content is designed to remain on the user's device unless the user explicitly chooses an export or backup action.

Official Privacy Policy:

https://tsidevstudio.com/privacy/micutvault

## Primary PIN protection

Access to the private vault is protected by a Primary PIN.

The supported PIN length is between 6 and 12 digits.

Users should keep their Primary PIN private and secure.

## Optional biometric unlock

MicutVault supports optional biometric authentication through Android-supported secure biometric methods.

Availability depends on the capabilities and security configuration of the user's device.

Biometric access is optional and does not replace the Primary PIN as the main vault credential.

## 9 disguise modes

MicutVault can appear using one of nine disguise modes:

- Calculator
- Notes
- Books
- Files
- Calendar
- Clock
- Tasks
- Scanner
- Recorder

The purpose of disguise mode is to make the application less obvious during everyday device use.

Calculator mode also functions as a real calculator.

Internal disguise and authentication implementation details are intentionally not published.

## Auto-lock

MicutVault can automatically lock after a period of inactivity.

Supported inactivity options include:

- 1 minute
- 3 minutes
- 5 minutes

Auto-lock helps reduce the amount of time the private vault remains accessible when the device is left unattended.

## Failed unlock protection

After repeated incorrect PIN attempts, MicutVault can temporarily block additional access attempts.

Supported lockout periods include:

- 10 minutes
- 15 minutes
- 30 minutes
- 1 hour
- 1 day

This protection is intended to slow repeated unauthorized access attempts.

## Optional intruder detection

Intruder detection is optional and disabled unless enabled by the user.

When enabled, and when the required Android camera permission has been granted, MicutVault can record a failed-access event and capture an intruder photo after repeated incorrect PIN attempts.

Intruder photos remain private to the application and are not intended to be placed in the public device gallery.

Behavior can vary depending on Android version, device capabilities and permission state.

## Encrypted 30-day Trash

Deleted private content can remain in an encrypted Trash for up to 30 days before permanent removal.

This gives users an opportunity to recover accidentally deleted content without moving it outside the protected environment.

## Encrypted backup and restore

MicutVault supports encrypted backup and restore.

Backup is designed to provide an additional recovery option without requiring mandatory cloud storage.

Users remain responsible for securely storing their backup files and recovery credentials.

## Private media and notes

The current Production version supports protected storage for:

- Photos
- Videos
- Audio
- Private notes

The vault also includes user-facing media features such as photo zoom, sorting and slideshow.

## Publication boundary

This public repository intentionally does not document:

- authentication internals
- encryption implementation details
- certificate or anti-redistribution logic
- private storage layouts
- security-sensitive disguise implementation details
- source code

Public documentation is limited to user-visible behavior, privacy principles and responsible security reporting.

## Official links

- Google Play: https://play.google.com/store/apps/details?id=com.tsi.micutvault
- MicutVault: https://tsidevstudio.com/apps/micutvault
- Privacy Policy: https://tsidevstudio.com/privacy/micutvault
- TSI Dev Studio: https://tsidevstudio.com
