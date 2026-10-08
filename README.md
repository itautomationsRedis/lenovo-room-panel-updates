# Room Panel Home updates

The current release is Room Panel Home **8.0**. It adds a Slack test button,
readable recent logs, five-second connection observations, immediate incident
alerts and recovery follow-ups, while retaining the two-hour summaries.

[Download RoomPanel-8.0.apk](RoomPanel-8.0.apk)

On an existing controller, open the APK in Files and choose Update. Open
Room Panel Home > Maintenance > Connection history > Send Slack test, then
Resume Zoom. The installed application's private Slack destination is retained.

To enable future automatic app updates once, open Maintenance > App updates >
Enable remote app updates, allow Room Panel Home to install apps, return and
choose Check for updates, then Resume Zoom. The app checks every 30 minutes;
installation waits for fresh evidence of an idle, connected controller.

The device checks package name, version, byte length, SHA-256 and the original
application signing certificate before an Android self-update. That certificate
fingerprint is `da718768c6df9130098ad7987766a4580f581e67c964a83de2510c99a4cc915e`.

Alerts record confirmed Zoom room errors or missing local network evidence;
unknown screens do not establish an outage. Recovery requires ten seconds of
fresh connected observations. Delivery waits/retries if Internet or Slack is
unavailable. Maintenance pauses new observations; queued alerts still retry.

Only standalone APKs, checksums, this guide and latest.json belong here.
Configured installer ISOs, Slack webhooks, device logs, signing keys and private
reporting state must remain private. Version 7.0 files are retained so clients
using a previously cached manifest can finish their download.
