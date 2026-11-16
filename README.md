# Awayy – build the APK (no Android Studio needed)

1. Create a free GitHub account and a **new public repo** (e.g. `awayy`).
2. Upload everything in this folder (drag & drop on github.com → "Add file" → "Upload files"). Keep the `.github` folder.
3. Open the **Actions** tab, wait ~5–8 min for "Build Awayy APK" to turn green.
4. Open **Releases** (right side of the repo). You'll see `Awayy.apk` and `Awayy-QR.png`.
5. On your Redmi A2: scan the QR (Google Lens / Camera) or open the release on the phone, download `Awayy.apk`, tap it, allow "Install unknown apps" for your browser when asked.

Updating: edit `www/index.html`, commit – a new release builds automatically.
Note: this is a debug-signed APK, fine for personal use (not for Play Store).
