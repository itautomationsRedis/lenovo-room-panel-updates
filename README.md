# Room Panel Home updates

This repository is reserved for signed Room Panel Home update packages and a
small `latest.json` update manifest. The device verifies the package name,
version, byte length, SHA-256 checksum and original signing certificate before
requesting an Android self-update.

Only the standalone launcher APK belongs here. Installer ISOs, Slack webhooks,
signing keys, device logs and private reporting state must never be published.

The original application certificate SHA-256 fingerprint is:
`da718768c6df9130098ad7987766a4580f581e67c964a83de2510c99a4cc915e`.

Updates retain application data and Zoom pairing. A device that has not enabled
Room Panel Home as an installation source must enable that once. Installation
waits for a fresh observation of an idle, connected Zoom controller.

The feed is not active until hosting and the first verified package are published.
