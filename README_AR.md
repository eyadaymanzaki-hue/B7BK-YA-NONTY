# B7BK YA NONTY ❤️ — Android APK Project

ده مشروع Android Studio جاهز لتحويل آخر نسخة من الموقع إلى APK.

## المميزات
- الموقع نفسه موجود داخل التطبيق، فلا يعتمد على Netlify لعرض الصفحة.
- الاتصال بالإنترنت مفعّل لـ Supabase والصور/الأغنية والمزامنة المشتركة.
- APK واحد مناسب لأجهزة Android الحديثة مثل Samsung A34 وHonor X8d.
- اختيار الملفات من داخل لوحة التعديل مدعوم.

## البناء
1. افتح المجلد `B7BK_YA_NONTY_APK_PROJECT` في Android Studio.
2. انتظر Gradle Sync.
3. من القائمة: **Build → Build APK(s)**.
4. هتلاقي الـAPK داخل `app/build/outputs/apk/`.

> المشروع يحتاج إنترنت أثناء أول Gradle Sync لتحميل Android Gradle Plugin وAndroidX WebKit. بعد تثبيت الـAPK، التطبيق نفسه يستخدم الإنترنت فقط لخدمات Supabase والموارد الخارجية.
