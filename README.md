<img src="https://i.ibb.co/8DHTgcCQ/Screenshot-2026-08-20-175247.png" alt="Screenshot 2026 08 20 175247" border="0">

# Fight Club APK — GitHub Build Project

## What this contains
- Single-file HTML app
- Login accepts any non-empty username/password
- Fight Club themed UI
- ENTER goes to Manifesto, not directly to Join
- Background music support
- Music button
- Logout
- Footer: Built by Bhim Mondal
- GitHub Actions workflow that builds an Android APK

## Add music
Put your legally obtained MP3 in:
`www/fight-club-theme.mp3`

The filename must be exactly:
`fight-club-theme.mp3`

If you do not add the MP3, the app will still build, but there will be no background music.

## Build on GitHub
1. Create a new GitHub repository.
2. Upload all files/folders from this project.
3. Open the repository's **Actions** tab.
4. Select **Build Fight Club APK**.
5. Click **Run workflow**.
6. When it finishes, open the workflow run.
7. Download the **Fight-Club-APK** artifact.
8. The artifact contains `app-debug.apk`.

No Android Studio project needs to be generated on your PC; GitHub Actions generates the Android platform and builds it.
