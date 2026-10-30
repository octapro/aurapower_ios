AURA POWER APP - Logo icon + splash screen ready. App opens https://octaprosolution.com/aura_power/

ANDROID APK (free, no computer setup):
1. github.com par free account banao, New repository banao.
2. "uploading an existing file" se is folder ki saari files upload karo (.github folder bhi).
3. "Actions" tab kholo -> "Build Android APK" -> 5-8 min wait.
4. Run complete hone par neeche "AuraPower-APK" download karo, zip kholo, app-debug.apk phone me install karo
   (phone me "Install unknown apps" allow karna padega).

ANDROID (Android Studio se): npm install; npx cap add android; npm run assets; npx cap open android -> Build APK.

iPHONE: Mac + Xcode chahiye. npm install; npx cap add ios; npm run assets; npx cap open ios -> apna iPhone select karke Run.
Apple Developer account ke bina app 7 din chalega; App Store/TestFlight ke liye $99/saal account.

iPHONE IPA (bina Mac ke):
1. Upar wale GitHub repository me ye files upload karo. Actions tab -> "Build iOS IPA (unsigned)" -> 10-15 min.
2. "AuraPower-IPA" download karo, unzip karo -> AuraPower.ipa milega.
3. Windows/Mac computer par Sideloadly (sideloadly.io) install karo, iPhone cable se jodo,
   IPA daalo aur apna Apple ID daalo -> Start. Phone me Settings > General > VPN & Device Management me app ko Trust karo.
   Free Apple ID se app 7 din chalega, phir Sideloadly se dobara install karo.
   Hamesha ke liye: Apple Developer account ($99/saal) + TestFlight/App Store.
