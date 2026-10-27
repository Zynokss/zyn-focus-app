# Troubleshooting

## My tasks disappeared

Check the website address and browser profile. Private browsing, clearing site data, a different browser, or an Android installation has separate storage. There is no account to sign into and no server copy of your tasks. If you have a matching [backup](backup-and-restore.md), preview and restore it. Avoid clearing more data while investigating.

## I cannot hear sound

Press play in the sound controls and check the master volume, individual layers, device volume, and audio output. Browsers can require a user action before playing. A sleep timer or selecting no active layers can stop the mix. Navigating away from the workspace stops its audio; closing the sound drawer does not. Offline sound needs a completed offline download first.

Saved YouTube links open an external website. In-app YouTube playback and search are currently unavailable.

## The timer or alert did not behave as expected

The timer uses a saved deadline. Return to the workspace to reconcile it after a suspended tab. Browser alerts require an open page and may need notification permission; browser installation does not add a push notification service. A long absence does not create a series of completed website sessions.

For existing Android preview users, check notification and precise-alarm permissions, notification volume, and device battery restrictions. Force-stopping the app cancels Android alarms. Hardware background behavior remains under review.

## Offline mode does not work

While online, open **Settings → Offline & install → Download for offline use** and wait for completion. The website must use HTTPS and the browser must support offline storage. Uncached pages and external links need a connection. Browser storage eviction can remove the prepared copy. Installation alone is not a guarantee that every asset has downloaded.

## A backup will not restore

Choose the original JSON file from the matching product platform. Website and Android formats are different. Do not rename a different file to JSON or edit private records to bypass validation. Restore replaces the workspace and needs enough free storage. Export your current data first. If a restore reports failure, keep both files and contact support without attaching them publicly.

## An Android update will not install

There is no approved public APK in this repository. Existing preview users should confirm the package came from the maintainer and has a compatible signature. Earlier locally signed previews and cloud-signed APKs use different keys. Export before any uninstall. Do not disable device protections to force an incompatible update.

## Report a problem

Use the repository's Issues tab for a reproducible bug. Include the website or Android version, operating system, browser where applicable, expected behavior, and steps to reproduce. Crop screenshots to remove private information. Do not include passwords, tokens, personal notes, or backup files. For private support or security reports, email [contact@zynoks.com](mailto:contact@zynoks.com).
