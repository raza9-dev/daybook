# Daybook – Android app

Tracks daily expenses, income, profit and notes. Works offline; data stays on the phone.
Back up from Settings → "Back up data".

## Get the APK without installing anything (GitHub)
1. Create a free account at github.com and make a new repository (e.g. "daybook").
2. On the repository page choose "uploading an existing file" and drag in ALL files
   and folders from this zip (including the hidden `.github` folder), then "Commit changes".
3. Open the "Actions" tab. The "Build Daybook APK" job runs by itself (about 3–5 minutes).
4. When it shows a green tick, open it and download "Daybook-APK" at the bottom.
   Unzip it to get `app-debug.apk`.
5. Copy the APK to your phone, tap it, and allow "Install unknown apps" when asked.

## Or with Android Studio
Open this folder in Android Studio, wait for the sync, then
Build → Build App Bundle(s) / APK(s) → Build APK(s).
