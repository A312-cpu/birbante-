# Compilare Birbante dal telefono con GitHub Actions

1. Crea un repository GitHub vuoto, ad esempio `birbante-app`.
2. Carica **tutto il contenuto di questa cartella**, mantenendo anche `.github/workflows/android-apk.yml`.
3. Apri il repository su GitHub e vai in **Actions**.
4. Seleziona **Build Birbante APK** e premi **Run workflow** (oppure fai un push sul branch `main`).
5. Quando il job termina con successo, apri la run e scarica l'artifact **Birbante-debug-apk**.
6. Estrai l'artifact e installa l'APK sul telefono Android.

Nota: questa pipeline genera una build `debug`, adatta alla prova. Non è una build firmata per la pubblicazione sul Play Store.
