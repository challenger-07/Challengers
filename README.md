# Challenger Android App

Ye app `https://challengers-live.netlify.app` ko kholti hai.
Data Supabase se aata hai, isliye internet chahiye.

## Phone se APK banana (GitHub Actions)

1. GitHub par free account banayein, aur **New repository** banayein (naam: `challenger-app`, Private).
2. Is zip ki files extract karke repository mein upload karein. `.github` folder ko bhi upload karna na bhulein.
3. Repository mein **Actions** tab kholein, **Build Android APK** chunein, aur **Run workflow** dabayein.
4. 5 se 10 minute mein build khatam hogi. Run par tap karke **challenger-debug-apk** download karein.
5. APK install karein. Chrome ko **Install unknown apps** ki permission deni hogi.

## Updates (live site se jud hai)

App `https://challengers-live.netlify.app` ko kholti hai. Netlify par nayi file deploy karte hi app mein wo change apne aap aa jayega. Har change ke liye naya APK nahi banana padega.

Sirf in cases mein naya APK banana hoga: app ka icon, naam ya package ID badalna ho, ya nayi permissions chahiye hon.

`www/index.html` sirf fallback hai, aur internet na hone par bhi kuch khul sakta hai.

## Play Store par dalna

1. Google Play Console account banayein ($25 ek baar).
2. Signed Android App Bundle (.aab) banayein, aur keystore file ko safe rakhein. Keystore kho gayi to app update nahi ho payegi.
3. Bundle Play Console par upload karein.

## iPhone (iOS)

iOS ke liye Mac, Xcode aur Apple Developer account ($99 saalana) chahiye.

## Test checklist (phone par)

- Admin login
- Test start, timer, submit
- Doubt post, reply aur file attach (file picker khulna chahiye)
- Doubt Room ON/OFF
- Leaderboard
