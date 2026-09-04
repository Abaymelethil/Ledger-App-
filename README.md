A journal + task + project-log app I built for myself — somewhere to dump daily notes, track todos, and keep a running log of what I'm building (versions, features, bugs) without juggling five different apps. Started as a plain HTML page, ended up wrapped into an Android app.

Features
Journal— dead simple, no clutter. just writwe.
Tasks — todo list with a built-in timer, so you can actually time yourself doing the thing instead of just listing it.
Notebooks — this is where it gets a bit much (in a good way). Keep proper notes with diagrams, flowcharts, and tables, log project versions/features/bugs as you go, and export any of it straight to PDF.
Backup & restore — export everything to a JSON file, restore from it later; auto-backs up every 3 days.
Dark/light theme with a few accent colors (rose, amber, sage, sky, lavender).

<img width="1200" height="2670" alt="Screenshot_20260905-013243_Ledger" src="https://github.com/user-attachments/assets/6bf702a6-cad8-447e-befe-047c8466fed5" />

<img width="1200" height="2670" alt="Screenshot_20260905-013004_Ledger" src="https://github.com/user-attachments/assets/96c23f65-4e78-49de-a4f4-39e462a83e92" />

Getting Started
Run the web app directly

Just open src/index.html in any modern browser no build step required.

Build the Android APK yourself
Open the android/ folder in Android Studio
Let Gradle sync
Build > Build Bundle(s) / APK(s) > Build APK(s)
The APK will be output to android/app/build/outputs/apk/
Download a pre-built APK

i dont know if i will release a new version, but all of you are more than welcome to contribute 

Tech Stack
HTML / CSS / JavaScript (core app logic)
Android Studio (WebView wrapper for APK packaging)
Development Notes

This app started as a plain HTML/JS project and was later wrapped into a native Android APK using Android Studio's WebView component.

License

MIT — see LICENSE for details.
