# graygate — Android releases

APKs for installing graygate on Android. graygate is not on Google Play, so it does not appear in
Google Play clients such as Aurora Store. There are three ways to get it, and all three install the
same APK signed with the same key, so you can switch between them without losing anything.

## 1. F-Droid repository (automatic updates)

Add graygate's own repository to an F-Droid app (F-Droid, Droid-ify, Neo Store):

```
https://fdroid.graygate.app/repo?fingerprint=ea93717e0fa47c8205bd562249b107fc7c18939d4bd2b542338b631769eda5e2
```

When you add it, check that the fingerprint the app shows matches the one above character for
character. If it does not match, do not add it. After that, the F-Droid app tells you about each new
release and installs it.

## 2. Obtainium (automatic updates from this page)

[Obtainium](https://obtainium.imranr.dev) follows the releases on this page:

1. Install Obtainium.
2. In Obtainium, tap **Add App** and enter `https://github.com/graygate/app-release`.
3. Install graygate from Obtainium. After the first install, check that the app's signing
   certificate SHA-256 matches the value in the release notes.

## 3. Direct download

Get the APK from [Releases](https://github.com/graygate/app-release/releases/latest) and install it.
Verify the download first: the release notes list the SHA-256 of the APK.

## Updating

- **Install over the previous release. Do not uninstall first.** Uninstalling deletes all
  conversations and keys on the device; they cannot be recovered.
- Since 0.8.0 every release uses the package name `app.graygate` and the same signing certificate,
  so Android accepts each new APK as an update. 0.6.4 and earlier used `com.joshephan.graygate`;
  0.8.0 installs next to such an old version as a separate app.

**Release announcements:** the Telegram channel [t.me/graygate](https://t.me/graygate) posts every
release with the download link, the release notes and the APK's SHA-256.

Source and product site: https://graygate.app
