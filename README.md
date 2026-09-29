# HTML to APK (built by GitHub, free)

## One-time setup
1. Make a free account at github.com.
2. Create a new repository (New > name it anything > Create).
3. Upload ALL files from this folder (Add file > Upload files).
   - The `.github` folder must be included (it is the builder).
   - If your browser skips it: Add file > Create new file, type
     `.github/workflows/build.yml` as the name, and paste the contents of that file.

## Every time you want an APK
1. Replace `www/index.html` with your HTML (put images/css/js in `www/` too).
2. Put your app name in `app-name.txt`.
3. Commit the changes. GitHub builds automatically (about 3-5 minutes).
   Watch progress in the "Actions" tab.
4. Open the "Releases" section on the repo's main page and tap `my-app.apk`
   to download it on your phone.
5. Open the downloaded file and tap Install.
   Android will ask once to allow "Install unknown apps" for your browser. Allow it.
