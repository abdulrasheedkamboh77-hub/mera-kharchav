MERA KHARCHA - ANDROID APK BANANE KE STEPS (Version 1.4.0)

Is zip mein 2 files hain:
  index.html  = aapki Mera Kharcha app
  build.yml   = GitHub ke liye hidayat jo APK banati hain

STEP 1 - GitHub account
  1. Chrome mein github.com kholein. Phone par: Chrome menu (3 dots) > "Desktop site" ON karein.
     (GitHub ki app use na karein, us mein upload nahi hota.)
  2. Sign up karein (free) aur email verify karein.

STEP 2 - Repository banayein
  1. Upar "+" > "New repository".
  2. Naam: mera-kharcha. "Private" chunein.
  3. "Add a README file" ko tick karein. "Create repository" dabayein.

STEP 3 - Files upload karein
  1. "Add file" > "Upload files".
  2. "choose your files" se index.html aur build.yml dono chunein.
  3. Green "Commit changes" dabayein.

STEP 4 - build.yml ko sahi folder mein bhejein
  1. File list mein build.yml kholein. Pencil icon (Edit) dabayein.
  2. Upar file ke naam ke box mein, build.yml se pehle ye likhein:  .github/workflows/
     Poora naam ban jaye:  .github/workflows/build.yml
  3. "Commit changes" dabayein, phir dobara "Commit changes". Build shuru ho jayegi.

STEP 5 - APK banne ka intezar
  1. "Actions" tab kholein. Agar "I understand my workflows" ka button aaye to dabayein.
  2. "Build APK" run kholein. 5-10 minute lagte hain. Green tick = tayyar.
  3. Run shuru na ho to: Actions > "Build APK" > "Run workflow".

STEP 6 - Download aur install
  1. Tayyar run ke andar neeche "Artifacts" mein MeraKharcha-APK dabayein (zip download hogi).
  2. Zip extract karein. app-debug.apk par tap karein aur Install dabayein.
  3. Phone rok de to "Install unknown apps" ki ijazat dein.

PURANA DATA
  Browser wali app mein: Settings > "Backup copy karein".
  Nayi Android app mein: Settings > Restore mein paste kar ke "Restore karein".
  Update se pehle har baar Backup zaroor lein.

MASLA AAYE
  Actions mein red cross par click karein, failed step ka screenshot bhej dein.
