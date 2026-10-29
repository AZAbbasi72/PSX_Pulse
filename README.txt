PSX Pulse - Android build (no coding needed)
1. Create a free account at github.com, click "+" > New repository, name it psx-pulse, tick Public, Create.
2. Click "uploading an existing file". Unzip this package first, then drag ALL files and folders
   (including .github, android, www) into the page. Click Commit changes.
   (If the .github folder does not upload: Add file > Create new file, name it .github/workflows/build.yml
    and paste the contents of that file from this package.)
3. Open the Actions tab. "Build APK" runs automatically (about 5-8 minutes). Wait for the green tick.
4. Click the run > Artifacts > PSX-Pulse-APK (downloads a zip). Unzip, copy app-debug.apk to your phone.
5. Tap the APK, allow "Install unknown apps" when asked. Done: PSX Pulse is on your home screen.
