# JAIMS Android GitHub Build Kit — Trial Update

## JAIMS ID Copy (Android trial prototype)
- Front/back images from Android file picker; A4 PDF internally; Print only.
- Fixed title `SALINAN KAD PENGENALAN`. No watermark/palang, custom title, Share or Export button.
- Trial limit: 3 submitted Android print jobs, stored locally in SharedPreferences.
- IMPORTANT: Android print dialog may expose Save as PDF. This prototype cannot block that OS feature.
- IMPORTANT: Trial count is NOT tamper resistant and may reset when app data is cleared or reinstalled.
- IMPORTANT: A print job submission is counted even if user cancels the OS print dialog. Real printer completion cannot be reliably verified.
- No real subscription/payment/license verification is implemented yet. RM3/month and RM10/year are product specifications only.
- Camera capture, edge detection, scan enhancements and live A4 preview are NOT implemented yet.

## JAIMS PDF Pro
- Existing early Android prototype unchanged. It is not a finished PDF editor.

## GitHub Actions build
1. Create a PRIVATE GitHub repository.
2. Upload the CONTENTS of this directory to the repository root, including `.github/workflows/android.yml`.
3. Open Actions > Build JAIMS Android APKs > Run workflow.
4. If successful, download the `JAIMS-Android-APK` artifact.

Builds have NOT been verified in an Android SDK or emulator in this environment. APKs are debug builds only. Do not publish as production or use real ID cards in testing.
