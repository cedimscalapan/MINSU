# MinSU Pathfinder

Offline-first Ionic Angular campus navigation and classroom timetable prototype. The bundled building layouts and schedules are **fictional demonstrations**, not verified MinSU data.

## Android APK

Open **Actions → Build Android APK → Run workflow** or push to `main`. After a successful run, download the `MinSU-Pathfinder-debug-APK` artifact from the workflow run; unzip it and install the `.apk` on Android. GitHub Actions must be enabled for the repository.

## Local development

`npm install && npm run build && npx cap add android && npx cap sync android`

## Scope

Offline 2D route graph, floor switching, campus room search, illustrative schedules, and Android distribution workflow. The initial Android APK is a development/demo release, not an authorized campus system.
