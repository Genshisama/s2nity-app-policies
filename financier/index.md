# Financier privacy policy

_Last updated: 24 November 2026_

Financier is a personal finance app for one person. It has no account, no
sign-up and no server.

## What we collect

Nothing. Financier does not collect, transmit or share any personal or
financial data. It has no analytics, no advertising, no crash reporting and
no network features.

## Where your data is

- Everything you enter stays **on your device**, in a database encrypted
  with SQLCipher. The encryption key is random, created on first run, and
  kept in the Android Keystore or iOS Keychain.
- Receipt photos you attach are stored encrypted in the app's private
  folder.
- The database is excluded from Android and iCloud system backups. Backups
  are the app's own job (below).

## Backups you make

When you back up, Financier writes an encrypted `.fbk` file
(AES-256-GCM, with a key derived from your backup passphrase using
Argon2id). You decide where it goes: the share sheet, or a folder you pick
(for example one that your Google Drive or OneDrive app syncs). That is the
only way your data leaves the device, and only when you set it up. Without
your passphrase nobody, including the developer, can open a backup. There is
no passphrase recovery.

## Permissions

| Permission | Why |
|---|---|
| Biometrics (fingerprint, Face ID) | Optional: unlock the app |
| Camera and photos | Optional: attach receipt photos |
| Notifications | Optional: reminders for bills, instalments and loan payments, scheduled on the device |
| Run at startup | Re-schedule those reminders after the phone restarts |

## Deleting your data

Uninstalling the app deletes everything on the device. Backup files you
saved elsewhere are yours to delete.

## Changes to this policy

If this policy changes, the date above is updated.

## Contact

Questions: <CONTACT_EMAIL>
