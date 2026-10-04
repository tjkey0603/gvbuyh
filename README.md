# Build the APK (no Android Studio needed)

1. Create a new GitHub repo and upload everything in this folder
   (including the hidden .github folder).
2. Open the repo's **Actions** tab -> **Build APK** -> wait ~5 min for the green tick.
3. Open the finished run, download the **cfd-profit-tracker-apk** artifact (zip),
   unzip it and you get app-debug.apk.
4. Send it to your phone, tap it, and allow "install unknown apps" when asked.

Your data is stored on-device (localStorage), so it stays on the phone it was entered on.
To change the app later: rebuild the web app, replace the contents of www/, push again.
