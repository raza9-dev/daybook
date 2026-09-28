# Daybook 2.0 – Android app

Daily expenses, income, profit and notes. Works offline; data stays on the phone.
Reports (week / month / year), history search, backup & restore, Excel (CSV) export, light/dark theme.

Build: GitHub Actions (`.github/workflows/build-apk.yml`) builds `Daybook.apk`.
The APK is signed with `app/daybook.keystore`, so every new build installs as an update.
Keep this repository private: the key and its password are in `app/build.gradle`.
