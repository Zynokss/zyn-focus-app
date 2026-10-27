# Installation and updates

## Website

Open [https://focus.zynoks.com/](https://focus.zynoks.com/) in a modern browser. No account or download is required for online use. JavaScript and browser storage must be available to save your workspace. Avoid private browsing if you want to keep your work between visits.

## Optional browser installation

1. Open the workspace while connected to the internet.
2. Open **Settings → Offline & install**.
3. Choose **Download for offline use** and wait for confirmation. This prepares the workspace, scenery, and original sounds.
4. Choose **Install Zyn Focus** if offered, or use your browser's install option. On iPhone, use Safari's **Share → Add to Home Screen** where available.
5. Open the installed workspace once, then check that it works without a connection before relying on it offline.

Installation and offline storage depend on browser support. The first download needs internet and HTTPS. Not every resource page is necessarily cached. Browser storage eviction or clearing site data can remove both the cache and saved work. Keep a [backup](backup-and-restore.md).

Browser installation is a shortcut to the web app, not a native desktop or iOS release. No Windows installer, Linux package, macOS installer, or iOS store build is verified.

## Android preview

There is no approved public Android download yet. Version 1.0.1 / build 3 is an internally distributed APK for Android 8.0 or later. Do not substitute an APK found on an unrelated site. A public release would need its own approved download link, checksum, and release notes.

For people who already received a preview directly from the maintainer:

1. Export an Android backup before changing versions.
2. Use only the APK supplied through the maintainer's approved channel. If the release supplies a checksum, verify the file against it before opening it.
3. Open the APK from your file manager. Android may ask you to allow installation from that app. Restrict that permission again afterward if you no longer need it.
4. For an update, install over the existing app when Android accepts the package and signature. If Android rejects it, keep your backup and contact support before uninstalling.
5. Allow notifications if you want session alerts. In **Space → Settings**, **Allow precise session alarms** opens the relevant Android permission settings where supported. Test alerts on your own device.

The cloud-signed preview and older locally built previews use different signing keys. Android cannot install one over the other. Export first; a change of signing key may require uninstalling the older app and restoring a backup after installation. Uninstalling without an export loses local data.

Android background audio, notifications, widgets, and battery restrictions need physical-device validation. This internal APK is not a Google Play release.

## Updating

- **Website:** open the current website. If the prepared offline workspace offers **Apply update & reload**, save any edits and choose it in Settings. Audio stops on reload; the timer recovers from its saved deadline.
- **Android preview:** install a newer approved APK with a compatible signature. There is no verified automatic update feed or public store listing. Do not assume an app changes when the website changes.

See [release status](../RELEASES.md) and [uninstall guidance](backup-and-restore.md#uninstalling).
