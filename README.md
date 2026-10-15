# Kharcha

**Know exactly where every rupee goes.** Kharcha spots every payment from your bank SMS (any bank, card or UPI app) and asks what it was for, so you always know where your money went. It works with whatever UPI apps you have (GPay, PhonePe, Paytm, slice, BHIM, your bank's app…): it finds them on your phone by itself.

## ⬇️ Download

**[Download Kharcha.apk](https://github.com/Pulin-PC/kharcha-releases/releases/latest/download/Kharcha.apk)**: open this link on your Android phone.

## Install it (5 minutes)

1. **Open the downloaded file.** If your phone asks, allow the app you downloaded it with (Chrome, WhatsApp, Files) to *install unknown apps*.
2. **If you see "App blocked to protect your device":** Google blocks downloaded apps that read SMS. To install anyway:
   - Open **Play Store** → tap your **profile picture** (top right) → **Play Protect** → **⚙️** (top right)
   - Turn **off** "Scan apps with Play Protect"
   - Open Kharcha.apk again and install
   - Go back and turn "Scan apps with Play Protect" **on** again
3. **If you see "App scan recommended" (Google Play Protect):** tap **Scan app**. It only sends the Kharcha app file to Google to check. None of your data is sent. The install continues after a few seconds.
4. **Unlock restricted settings** (Android 13 and newer block SMS and Accessibility for downloaded apps):
   **Settings → Apps → Kharcha → ⋮ (top right) → Allow restricted settings**
5. **Open Kharcha, sign in with Google** (one tap), and set a 4-digit passcode.
6. **Follow the setup.** It asks for each permission one at a time, and opens the right Settings page for you when Android needs a switch flipped:
   - **Read SMS:** how Kharcha spots payments
   - **Notifications:** a reminder if the reason bar is ever hidden
   - **Display over other apps:** the "what was it for?" bar
   - **Accessibility → Kharcha payment prompt:** pops the bar up the moment a UPI app opens (it only sees *which* app is open, never what's on screen)
   - **Run in background:** so Android doesn't close Kharcha
   On Xiaomi, Redmi, Poco, Oppo, Vivo, Realme or OnePlus, also turn on **Autostart** for Kharcha (App info).

Done. At the end of setup Kharcha offers to bring in your past spends from SMS already on your phone. Missed a step? Tap your **profile picture** (top right) → **Payment detection**.

## Updates

Kharcha tells you when there's a new version (**"New Kharcha version → Update"** on the Home screen). Tap **Update**. The first time, Android asks you to allow Kharcha to install updates; turn that on once. If Play Protect asks to scan it, tap **Scan app**. Your data stays exactly as it is.

## Privacy

- Your **spends, payees and SMS stay on your phone**. They are never sent anywhere. No ads.
- You sign in with Google so I can count how many people use Kharcha. The server gets only your **Google name and email**, and **each time you open the app** (time, app version, phone model).
- **Delete your account any time:** profile picture (top right) → **Manage your account → Delete my account**. That erases your sign-in and open history from the server. Your expenses on the phone aren't touched. Can't open the app any more? Email pulin.chaudhari@gmail.com and I'll delete it.
- Your data is encrypted with your passcode and your phone's secure chip.
- SMS are read only to find payments. The message text is never stored, and nothing is marked as read.
- Kharcha also checks this page for a newer version of itself.

## Is this file really from me?

Every update is signed with the same private key, and Kharcha refuses to install anything signed with a different one. If you want to check, the signing certificate's SHA-256 fingerprint is:

`de:71:83:01:98:57:90:1c:d2:2b:67:b7:36:fd:04:cb:32:3b:77:6a:fe:39:cf:c7:1c:64:82:74:5e:e3:9c:eb`
