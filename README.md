# Zencode Releases

This repository is the official distribution channel for Zencode desktop releases and automatic updates.

Release assets may include:

- signed and notarized macOS installers;
- signed Windows installers;
- Linux AppImages;
- update metadata and differential-download blockmaps; and
- a `SHA256SUMS.txt` integrity manifest.

Download Zencode only from this repository's **Releases** page. Stable releases are marked as latest; preview builds are clearly marked as prereleases.

## Authenticity and integrity

- On macOS, verify that the application is signed by Zencode's identified Apple developer and passes Gatekeeper validation.
- On Windows, inspect the installer's digital-signature properties before running it.
- On every platform, compare the downloaded file with the matching entry in `SHA256SUMS.txt`.

If a signature, checksum, or release asset does not match, do not install it. Report suspected release-security problems privately through this repository's **Security** tab.

## Licensing

Zencode is proprietary software. Copyright © 2026 Zencode. All rights reserved. Availability of release files does not grant permission to redistribute, modify, reverse engineer, or repackage Zencode. Third-party components remain subject to their respective licenses and notices.

This repository contains distribution artifacts and release records, not the Zencode application source code.
