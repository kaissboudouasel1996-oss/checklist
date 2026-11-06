# Good Vibes Checklist

Checklist app for the Panini Stitch Good Vibes! trading cards (209 cards plus bonus cards). The page in `www/index.html` is wrapped as an Android app with Capacitor, and GitHub builds the APK for you.

## Get the APK

1. Create a new repository on GitHub and upload everything in this folder, including the hidden `.github` folder.
2. Open the repository's **Actions** tab. The **Build APK** workflow starts on its own after the upload. If it doesn't, open it and press **Run workflow**.
3. When the run turns green (about 5 minutes), open it and download **good-vibes-checklist-apk** from the Artifacts section at the bottom.
4. Unzip it and send `app-debug.apk` to your phone. Open it, and allow installs from your file manager or browser if Android asks.

## Notes

- Tap the + button in the app to add more checklists from a `.checklist.json` file. A sample is in the `samples` folder.
- Under "Swap with a friend" you can show a QR code of your spares and needs, or scan a friend's code with the camera, a photo, or by pasting the code. Camera scanning needs a camera permission the first time.
- Progress is saved on the phone, inside the app. Uninstalling the app erases it.
- The APK is a debug build, which installs fine but is not meant for the Play Store.
- Fonts load from Google Fonts when online and fall back to system fonts offline.
