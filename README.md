# chainbreakers-backup
chainbreakers-backup
Homepage and privacy policy for **CHAINBREAKERS Backup**, a private, single-user Google OAuth app.

**[Homepage](./) · [Privacy Policy](./#privacy)**

## What this is

A personal backup job for a home game server. Each night it uses
[rclone](https://rclone.org) to copy that server's game-world backups to its owner's own Google
Drive. Files are **encrypted on the server before upload**, so Google only ever stores unreadable data.

This repository exists only because Google requires a public homepage and privacy policy before
an OAuth app can leave "Testing" mode. It holds that one page and nothing else.

## Scope of access

The app requests a single Google permission, `drive.file`, which limits it to **files it created
itself**. It cannot see or touch anything else in the owner's Drive, or any other Google service.

## What is *not* in this repository

- No source code, scripts or configuration
- No credentials, tokens, client secrets or encryption passphrases
- No backups or user data

## Not for public use

This app has one user: its owner. It isn't offered, supported or available to anyone else.
