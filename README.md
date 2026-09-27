# Crash Rush 3D — Android build

## Get your APK
1. Create a new empty repo on https://github.com (this is a SEPARATE repo from
   scrapheap-tycoon — don't push this into that one).
2. Push this folder:
   ```
   git init
   git add .
   git commit -m "Crash Rush 3D first build"
   git branch -M main
   git remote add origin <your-new-repo-url>
   git push -u origin main
   ```
3. Repo's "Actions" tab → wait for the green checkmark (~3-5 min).
4. Open the run → scroll to "Artifacts" → download `crashrush3d-debug-apk` →
   unzip → `app-debug.apk` → install on your phone the same way as before.

## Before Play Store
Same checklist as Scrapheap Tycoon's PLAYSTORE-LAUNCH-KIT.md — signed release
AAB, real icon, privacy policy, store listing. This is a second, separate app,
so it needs its own Play Console listing.
