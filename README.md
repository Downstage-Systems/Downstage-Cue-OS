# Downstage Cue OS

Release firmware for the Downstage Cue lights (the One's own is downstage-os). Only the files a light installs live here; the source is
private.

| Light | Folder | Install on |
|---|---|---|
| Cue Lite | `firmware/DSL/` | the Cue Lite (Waveshare AMOLED 1.8) |
| Cue 360 | `firmware/DS3/` | the Cue 360 (Waveshare ESP32-S3-Matrix) |
| Cue Mini | `firmware/DSM/` | the Cue Mini (Waveshare ESP32-S3-Matrix, the flat tile) |

`latest.json` names the newest release for each light. `CHANGELOG.md` says what changed.

## Updating a light

**From its page (the easy way).** Open the light's page (its address, or scan the code on its
screen), go to **Device**, and look under **Update**. If the phone or laptop you are using has the
internet, the page shows when a newer release is out: tap **Install**. The light downloads nothing
itself; your browser fetches the file and hands it over. The light restarts on the new firmware in
about a minute.

**From a file.** Download the light's newest `.bin` from its folder above, then on the light's
page under **Device > Update** choose the file and press **Install the file**. Handy at a venue with
no internet: download at home, install at the show.

A light only takes a file made for it, and never one older than the firmware it runs (from 0.186.3 on).
Choose the wrong one and it says so and changes nothing.

Update between shows, not during one: the light restarts.

## Support

hello@downstage.systems - [downstage.systems](https://downstage.systems)

These files are for Downstage hardware. © 2026 Downstage Systems LLC. All rights reserved.
