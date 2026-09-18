# Privacy Policy — ScreenPeek

**Last updated: 18 September 2026**

ScreenPeek is an Android app that watches your phone's front camera while you use it and alerts you
when someone other than you appears to be looking at your screen.

## Summary

- **Your camera images never leave your device.** Face detection runs entirely on your phone, and
  snapshots are stored only in the app's own storage.
- **The app shows banner advertisements** supplied by Google AdMob. AdMob collects advertising data,
  described below. This is the only part of ScreenPeek that sends anything over the internet.
- There are no accounts, and we operate no servers of our own. We never receive your photos.

## Camera and photos

ScreenPeek analyses frames from the front camera to detect faces. Analysis happens **on your device**
using a face-detection model bundled inside the app. No frame is uploaded, and detection works with
the phone offline or in airplane mode.

Most frames are examined and discarded immediately. A photo is saved **only** when the app confirms
that a second face has been looking at your screen for about a second.

| What | Where | Who can read it |
|---|---|---|
| Snapshots of detected peeks (JPEG) | Your device, in the app's private storage | You, and any app you explicitly share a photo with |
| A log of detection times (CSV) | The same private folder | You |
| Your settings | Android `SharedPreferences`, private to the app | You |
| An optional gallery copy | `Pictures/ScreenPeek`, only if you enable that setting | You and any app with photo access |

Snapshots stay until you delete them from the app's History screen or uninstall the app.
Uninstalling removes everything in the app's private storage. Copies you chose to save to your
gallery are **not** removed by uninstalling — delete those from your Photos app.

**We never receive, transmit or have access to these photos.**

## Advertising (Google AdMob)

ScreenPeek displays a banner advertisement at the bottom of its screens, served by Google AdMob.

To serve and measure those ads, AdMob may collect and process:

- Your device's **advertising ID** (a resettable identifier)
- **Device information** such as model, operating-system version and language
- **Ad interaction data** such as impressions and clicks
- **Coarse location** derived from your IP address (country or region level, not precise location)

AdMob uses this to select ads, measure their performance, and prevent fraud. This data goes to
Google, not to us. Google's handling of it is governed by their own policies:

- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses data from partner apps: https://policies.google.com/technologies/partner-sites
- AdMob and user data: https://support.google.com/admob/answer/6128543

**Your camera images and snapshots are never used for advertising and are never shared with AdMob
or any other third party.**

### Your choices about ads

- **Reset or delete your advertising ID:** Android Settings → Privacy → Ads.
- **Opt out of ad personalisation:** the same screen. You will still see ads, but less targeted ones.
- If you are in a region that requires a consent prompt, ScreenPeek will ask for your choice before
  serving personalised ads, and you can change that choice later.

## Children

ScreenPeek is not directed at children and should not be used by anyone under 13.

## Photographs of other people

ScreenPeek's purpose is to capture a photo of whoever is looking at your screen. That photo may
include a person who has not consented to being photographed.

- Those photos stay on your device and are never transmitted by the app.
- Android shows a green camera indicator while ScreenPeek is watching, and requires a permanent
  notification, so the camera is never in use invisibly.
- **You are responsible for how you use these photos.** Laws on photographing and recording people
  differ by country, and some places restrict recording without consent even on your own device.
  Please use ScreenPeek only where it is lawful for you to do so.

## Changes

If this policy changes, the "Last updated" date changes with it, and the revised policy is published
at the same URL.

## Contact

Questions about this policy: **<your contact email>**

<!--
BEFORE PUBLISHING:
  1. Replace <your contact email> with a real, monitored address. Play requires one.
  2. Host this at a public URL (GitHub Pages renders Markdown directly) and put that URL in Play
     Console under both Store listing and App content > Privacy policy.
  3. The URL must stay reachable for as long as the app is published.
-->
