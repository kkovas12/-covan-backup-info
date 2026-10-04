# covan-backup

A personal, single-user tool that stores encrypted database backups in the owner's own Google Drive.

## What it accesses
It uses only the `drive.file` permission: it can see and manage files and folders that it created
itself, and nothing else in the Google Drive account.

## Data handling
- The files it uploads are database backups encrypted with `age` before they leave the server.
- Nothing is collected, shared, sold, or sent to any third party. There are no other users.
- The only data stored is the OAuth token on the owner's own server, which the owner can revoke
  at any time at https://myaccount.google.com/permissions.

## Contact
Open an issue in this repository.
