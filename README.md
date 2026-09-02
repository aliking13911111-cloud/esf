# میدان بزرگ — GitHub APK Builder

این پروژه، نسخه V26 بازی «میدان بزرگ» را داخل یک Android WebView بسته‌بندی می‌کند.

## ساخت APK در GitHub

1. تمام فایل‌های این پوشه را داخل Repository خود قرار دهید.
2. حتماً فایل `.github/workflows/android-apk.yml` هم در Repository باشد.
3. از بخش **Actions**، Workflow با نام **Build Android APK** را اجرا کنید.
4. پس از موفقیت، از بخش **Artifacts** فایل `meydan-bozorg-debug-apk` را دریافت کنید.

Workflow با JDK 17، Android SDK API 37، Android Gradle Plugin 9.3.0 و Gradle 9.5.1 ساخته می‌شود.

## نکته

نسخه فعلی HTML برای Three.js از CDN استفاده می‌کند؛ بنابراین ممکن است برای بارگذاری کامل بازی به اینترنت نیاز داشته باشد.
