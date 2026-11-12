# APK per GitHub Actions bauen (kostenlos)
1. Auf github.com ein neues Repository anlegen (z.B. "apk-app"), leer, ohne README.
2. Diesen Ordner hochladen: Im Repo "uploading an existing file" waehlen und ALLE Dateien inkl. des Ordners .github hineinziehen, committen. (Oder: git init, git add ., git commit, git remote add, git push -u origin main.)
3. Reiter "Actions": Der Build startet automatisch (ca. 3-5 Min.).
4. Danach unter "Releases" die neueste Version oeffnen, dort liegt app.apk. Link-Form: https://github.com/BENUTZER/REPO/releases/latest/download/app.apk
5. APK aufs Handy laden und installieren (Installation aus unbekannten Quellen erlauben).
