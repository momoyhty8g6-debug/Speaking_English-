# ٢٠٠٠ جملة إنجليزية — Android APK

هذا المشروع يحوّل نسخة الويب إلى تطبيق Android محلي باستخدام WebView.

## البناء محليًا
```bash
gradle assembleDebug
```

الملف الناتج:
`app/build/outputs/apk/debug/app-debug.apk`

## GitHub Actions
ارفع المشروع إلى مستودع GitHub على الفرع `main`، وسيعمل ملف `.github/workflows/build.yml` تلقائيًا، أو شغّله يدويًا من Actions > Build APK.
