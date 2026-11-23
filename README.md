# CanonMultiCam Pro (V13 Hive-Mind Gold Master)

منظومة مراقبة وتحكم إخراجي متعددة الكاميرات (حتى 4 كاميرات Canon في نفس الجلسة عبر CCAPI و PTP/IP) مبنية بلغة Kotlin و Jetpack Compose و OpenGL ES 3.0.

## المزايا المعمارية
- **محرك رسوميات OpenGL ES 3.0**: عرض رباعي 60fps مع أداة LUT 3D (.cube)، Focus Peaking، False Color، Zebra، شبكات 9:16 و 2.39:1 و 3x3، وفك ضغط عدسات Anamorphic.
- **مخزن ثلاثي محصّن (Pinned Triple-Buffer)**: يمنع تضارب القراءة والكتابة بين خيوط الشبكة وفك التشفير.
- **حارس التسجيل والتعريض**: مزامنة التعريض مع تعويض ISO التلقائي، كشف انحراف التعريض (DRIFT)، وإنذار صوتي واهتزازي فوري عند توقف التسجيل.
- **مسجّل اللقطات والكلاكيت**: تسجيل رقم اللقطة، تمييز اللقطات الممتازة (★ GOOD)، وتصدير جدول Markers CSV متوافق مع Adobe Premiere Pro و DaVinci Resolve.

## البناء والاختبار عبر GitHub Actions
ارفع المشروع إلى مستودع GitHub على فرع `main`؛ سيعمل تلقائياً خط التحقق (`Detekt` -> `Unit Tests` -> `Android Lint` -> `Assemble APK`) ويتيح تحميل `CanonMultiCamPro-V13-Verified-APK`.
