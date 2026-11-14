# تنزيلات منظومة صولة السحابية SPOS Solah Cloud

مستودع التوزيع الرسمي — كل حزم المنصات تُنشر هنا وتُقدَّم تلقائياً عبر قنوات التحديث في التطبيق.

## الروابط الدائمة (آخر ريليز كامل — v1.17.106)

| المنصة | الرابط |
| --- | --- |
| ويندوز (المُطلِق الخفيف) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Setup.exe |
| ويندوز (حزمة x64) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Windows-x64.zip |
| لينكس (المثبّت الخفيف) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Setup-linux-x64.run |
| لينكس (المثبّت الكامل دون اتصال) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Setup-Offline-linux-x64.run |
| لينكس (حزمة x64) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Linux-x64.zip |
| أندرويد (APK) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Android.apk |

## v1.17.106 — الريليز الكامل (latest): إغلاق ثغرة دخول المنتهي اشتراكه + تحليلات التفعيل للمالك + إصلاح فيضان QR

**المنتهي لا يدخل ولا يجلس بعد اليوم** — كان الدخول لا يفحص الاشتراك إطلاقاً والجلسة الحية تعمل 30 يوماً مهما انتهى الاشتراك (وثغرة أعمق: مسار استعادة الجلسة المعفى من بوابة البنية كان يسقي الأجهزة القديمة بلا قفل محلي فيعمل محلياً إلى ما لا نهاية). من الآن: حارس على الدخول (منتهٍ/موقوف/ملغى = رفض صادق وبياناتكم محفوظة) + إبطال لحظي عبر SSE تهبط معه كل أجهزة المنتهي لشاشة الدخول خلال أجزاء ثانية + أرضية بنية تضمن أن كل عابر للبوابة يملك القفل المحلي. وفي لوحة المالك:

- **تحليلات التفعيل** (قسم جديد): قمع خمس خطوات (أنشأ ← عاد ← أضاف منتجاً ← باع ← دفع) بنسب التحويل والمتسربين + نبض المتاجر (نشطة اليوم/الأسبوع/الشهر/خاملة) + خريطة كل حساب بمرحلته + «من يدخل»: آخر 80 دخولاً بمنصة الجهاز والمحاولات الفاشلة والمتصل الآن + بطاقة «نقطة الفشل»: العالقون بلا أي منتج بترتيب الأقدم مع زر واتساب برسالة تفقّد جاهزة.
- **إصلاح فيضان رمز الدفع QR** في الويب والكمبيوتر: الرمز كان يُخبز بمقاس 512 بكسل داخل SVG فيفيض فوق بطاقته ويغطي المحتوى — صار سائلاً يلتزم بحاويته (210×210) + درع واجهة يمنع العودة، ورمز مصادقة المالك أُصلح بالمثل.

- سجل التغيير الكامل: https://github.com/spos-systems/downloads/releases/tag/v1.17.106
- أندرويد (APK — versionCode 108): https://github.com/spos-systems/downloads/releases/download/v1.17.106/SPOS-Solah-Cloud-Android-v1.17.106.apk
- أندرويد (Play Store AAB): https://github.com/spos-systems/downloads/releases/download/v1.17.106/SPOS-Solah-Cloud-Android-v1.17.106-PLAY-UPLOAD.aab
- أندرويد (خريطة R8 للتشويش): https://github.com/spos-systems/downloads/releases/download/v1.17.106/SPOS-Solah-Cloud-Android-v1.17.106-mapping.txt.gz
- ويندوز (حزمة x64): https://github.com/spos-systems/downloads/releases/download/v1.17.106/SPOS-Solah-Cloud-Windows-x64-v1.17.106.zip
- ويندوز (المثبّت الكامل NSIS): https://github.com/spos-systems/downloads/releases/download/v1.17.106/SPOS-Solah-Cloud-Windows-Setup-x64-v1.17.106.exe
- لينكس (AppImage): https://github.com/spos-systems/downloads/releases/download/v1.17.106/SPOS-Solah-Cloud-Linux-x64-v1.17.106.AppImage
- لينكس (deb): https://github.com/spos-systems/downloads/releases/download/v1.17.106/SPOS-Solah-Cloud-Linux-x64-v1.17.106.deb
- لينكس (المثبّتان الرسوسيان): https://github.com/spos-systems/downloads/releases/download/v1.17.106/SPOS-Solah-Cloud-Setup-linux-x64-v1.17.106.run · https://github.com/spos-systems/downloads/releases/download/v1.17.106/SPOS-Solah-Cloud-Setup-Offline-linux-x64-v1.17.106.run
- البصمات: [SHA256SUMS.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.106/SHA256SUMS.txt) · [SHA256SUMS-Linux.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.106/SHA256SUMS-Linux.txt) · [SHA256SUMS-Android.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.106/SHA256SUMS-Android.txt)

## v1.17.105 — سابقاً: دفع الاشتراك برمز QR من الهاتف + اشتراك الهاتف بمعايير Play المدققة

**دفع الاشتراك صار من هاتفك وأنت على الكمبيوتر** — بعد اختيار الباقة والمتابعة للدفع على الكمبيوتر لا يُطلب إرفاق وصل إطلاقاً (الوصل من تطبيق مصرفي على الهاتف أصلاً): يظهر رمز QR حي من الخادم يمسحه المستخدم بكاميرا هاتفه فتفتح صفحة دفع بهوية المنظومة بالضبط — المبلغ، بيانات الحوالة بأزرار نسخ، مرجع الحوالة، رفع الوصل من الكاميرا أو المعرض، الإرسال — وشاشة الكمبيوتر تنقلب تلقائياً لبطاقة «وصل طلبك — قيد المراجعة» فور الإرسال (استطلاع كل 4 ثوانٍ). رمز لمرة واحدة بصلاحية 24 ساعة ولا دخول مطلوباً على هاتف الدافئ. وفي الهاتف:

- صفحة الاشتراك بنص إخباري حيادي واحد بلا زر ولا وصلة: «الشراء والتجديد — من موقع المنظومة أو تطبيق الكمبيوتر» — على التحقق الرسمي من سياسة Play (الدفع والتشجيع عليه حصراً هو الممنوع، أما إدارة الاشتراك فمسموحة صراحة) عادت إدارة الاشتراك كاملة: بطاقة «فتراتي» (تثبيت/تشغيل مجدولة/عودة للتلقائي) وبطاقة «طلبك قيد المراجعة» بحالتها وتواريخها.
- شاشات الإيقاف عادت فيها أزرار الدعم بصياغة دعم خالص «فريق الدعم جاهز للمساعدة» على كل المنصات، وقنوات الدعم أقرب في نافذة التجديد وتبويب الإعدادات.
- خطة ب الآمنة: إن تعذر تجهيز الرمز (خادم لم يُحدّث بعد) تظهر الواجهة الكلاسيكية بدل طريق مسدود — والهاتف والشاشات الضيقة تبقى على الرفع المباشر كما كان.
- حركات إغلاق النوافذ سلسة الآن في كل مكان (المحلية والسحابية معاً) — غلاف الحوارات يدير طور الخروج مركزياً.

- سجل التغيير الكامل: https://github.com/spos-systems/downloads/releases/tag/v1.17.105
- أندرويد (APK — versionCode 107): https://github.com/spos-systems/downloads/releases/download/v1.17.105/SPOS-Solah-Cloud-Android-v1.17.105.apk
- أندرويد (Play Store AAB): https://github.com/spos-systems/downloads/releases/download/v1.17.105/SPOS-Solah-Cloud-Android-v1.17.105-PLAY-UPLOAD.aab
- أندرويد (خريطة R8 للتشويش): https://github.com/spos-systems/downloads/releases/download/v1.17.105/SPOS-Solah-Cloud-Android-v1.17.105-mapping.txt.gz
- ويندوز (حزمة x64): https://github.com/spos-systems/downloads/releases/download/v1.17.105/SPOS-Solah-Cloud-Windows-x64-v1.17.105.zip
- ويندوز (المثبّت الكامل NSIS): https://github.com/spos-systems/downloads/releases/download/v1.17.105/SPOS-Solah-Cloud-Windows-Setup-x64-v1.17.105.exe
- لينكس (AppImage): https://github.com/spos-systems/downloads/releases/download/v1.17.105/SPOS-Solah-Cloud-Linux-x64-v1.17.105.AppImage
- لينكس (deb): https://github.com/spos-systems/downloads/releases/download/v1.17.105/SPOS-Solah-Cloud-Linux-x64-v1.17.105.deb
- لينكس (المثبّتان الرسوسيان): https://github.com/spos-systems/downloads/releases/download/v1.17.105/SPOS-Solah-Cloud-Setup-linux-x64-v1.17.105.run · https://github.com/spos-systems/downloads/releases/download/v1.17.105/SPOS-Solah-Cloud-Setup-Offline-linux-x64-v1.17.105.run
- البصمات: [SHA256SUMS.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.105/SHA256SUMS.txt) · [SHA256SUMS-Linux.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.105/SHA256SUMS-Linux.txt) · [SHA256SUMS-Android.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.105/SHA256SUMS-Android.txt)

## v1.17.100 — سابقاً: إقلاع فوري بلا انتظار الشبكة

**التطبيق لم يعد ينتظر الإنترنت ليفتح** — كان إقلاع التطبيق ينتظر نداءً سحابياً بلا مهلة (وهو فحص لوحة مالك المنصّة لا يعني الكاشير أصلاً)، فمع واي فاي ضعيف يعلّق النداء وتظهر شاشة «تعذر الاتصال بالخدمة السحابية» وزر إعادة المحاولة. من الآن: نافذة الدخول تفتح فور اكتمال التهيئة المحلية مهما كانت حالة الشبكة، ومهلة 20 ثانية لكل نداء سحابي، وعودة الإنترنت تجدد الجلسة والترخيص خلال ثوانٍ تلقائياً. يشمل أيضاً إصلاحات التجربة الخمسة من v1.17.99 (كومبوهات طباعة مصممة + بطاقات طابعات جديدة + كلمة المرور لا تبقى في صفحة الدخول + بلا زر مشاركة + شريط التنقل بضغط الزر حصراً).

- سجل التغيير الكامل: https://github.com/spos-systems/downloads/releases/tag/v1.17.100
- أندرويد (APK — versionCode 102): https://github.com/spos-systems/downloads/releases/download/v1.17.100/SPOS-Solah-Cloud-Android-v1.17.100.apk
- أندرويد (Play Store AAB): https://github.com/spos-systems/downloads/releases/download/v1.17.100/SPOS-Solah-Cloud-Android-v1.17.100-PLAY-UPLOAD.aab
- ويندوز (حزمة x64): https://github.com/spos-systems/downloads/releases/download/v1.17.100/SPOS-Solah-Cloud-Windows-x64-v1.17.100.zip
- ويندوز (المثبّت الكامل NSIS): https://github.com/spos-systems/downloads/releases/download/v1.17.100/SPOS-Solah-Cloud-Windows-Setup-x64-v1.17.100.exe
- لينكس (AppImage): https://github.com/spos-systems/downloads/releases/download/v1.17.100/SPOS-Solah-Cloud-Linux-x64-v1.17.100.AppImage
- لينكس (deb): https://github.com/spos-systems/downloads/releases/download/v1.17.100/SPOS-Solah-Cloud-Linux-x64-v1.17.100.deb
- البصمات: [SHA256SUMS.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.100/SHA256SUMS.txt) · [SHA256SUMS-Linux.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.100/SHA256SUMS-Linux.txt) · [SHA256SUMS-Android.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.100/SHA256SUMS-Android.txt)

## v1.17.97 — سابقاً: الدخول بلا إنترنت بكلمات محفوظة + ربط الطابعات

**كلمات المرور محفوظة والدخول بلا إنترنت يعمل** — بعد أول دخول ناجح تُعبأ شاشة الدخول كاملة، ومع انقطاع الإنترنت يفتح التطبيق بوضع «بلا إنترنت» (البيع واليومية محلياً والمزامنة تلقائية عند عودة الاتصال). يشمل أيضاً: بطاقة ربط الطابعات في الكمبيوتر (إيصال/A4/ملصقات + طباعة مباشرة بلا نافذة)، إصلاح زر طباعة الإيصال على الكمبيوتر، طباعة A4 فورية، وإزالة إذن الكاميرا نهائياً من أندرويد.

- سجل التغيير الكامل: https://github.com/spos-systems/downloads/releases/tag/v1.17.97
- أندرويد (APK — versionCode 99): https://github.com/spos-systems/downloads/releases/download/v1.17.97/SPOS-Solah-Cloud-Android-v1.17.97.apk
- أندرويد (Play Store AAB): https://github.com/spos-systems/downloads/releases/download/v1.17.97/SPOS-Solah-Cloud-Android-v1.17.97.aab
- ويندوز (حزمة x64): https://github.com/spos-systems/downloads/releases/download/v1.17.97/SPOS-Solah-Cloud-Windows-x64-v1.17.97.zip
- ويندوز (المثبّت الكامل NSIS): https://github.com/spos-systems/downloads/releases/download/v1.17.97/SPOS-Solah-Cloud-Windows-Setup-x64-v1.17.97.exe
- لينكس (AppImage): https://github.com/spos-systems/downloads/releases/download/v1.17.97/SPOS-Solah-Cloud-Linux-x64-v1.17.97.AppImage
- لينكس (deb): https://github.com/spos-systems/downloads/releases/download/v1.17.97/SPOS-Solah-Cloud-Linux-x64-v1.17.97.deb
- البصمات: [SHA256SUMS.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.97/SHA256SUMS.txt) · [SHA256SUMS-Linux.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.97/SHA256SUMS-Linux.txt) · [SHA256SUMS-Android.txt](https://github.com/spos-systems/downloads/releases/download/v1.17.97/SHA256SUMS-Android.txt)

## رقع المنصات المستقلة (T291 — تصل عملاء المنصة فقط دون بقية المنصات)

### v1.17.97 — الدخول بلا إنترنت + ربط الطابعات (رقع المنصات)
- أندرويد: https://github.com/spos-systems/downloads/releases/download/android-v1.17.97/SPOS-Solah-Cloud-Android-v1.17.97.apk
- ويندوز: https://github.com/spos-systems/downloads/releases/download/windows-v1.17.97/SPOS-Solah-Cloud-Windows-x64.zip
- ويندوز (المُطلِق): https://github.com/spos-systems/downloads/releases/download/windows-v1.17.97/SPOS-Solah-Cloud-Setup.exe
- لينكس (الحزمة + AppImage + deb + المثبّتان): https://github.com/spos-systems/downloads/releases/tag/linux-v1.17.97
- البصمات: [SHA256SUMS.txt](https://github.com/spos-systems/downloads/releases/download/windows-v1.17.97/SHA256SUMS.txt) · [SHA256SUMS-Linux.txt](https://github.com/spos-systems/downloads/releases/download/linux-v1.17.97/SHA256SUMS-Linux.txt) · [SHA256SUMS-Android.txt](https://github.com/spos-systems/downloads/releases/download/android-v1.17.97/SHA256SUMS-Android.txt)

### v1.17.96 — القفل الدائم للهوية (رقع المنصات قبل الريليز الكامل)
- أندرويد: https://github.com/spos-systems/downloads/releases/download/android-v1.17.96/SPOS-Solah-Cloud-Android-v1.17.96.apk
- ويندوز: https://github.com/spos-systems/downloads/releases/download/windows-v1.17.96/SPOS-Solah-Cloud-Windows-x64.zip
- ويندوز (المُطلِق): https://github.com/spos-systems/downloads/releases/download/windows-v1.17.96/SPOS-Solah-Cloud-Setup.exe
- لينكس (الحزمة + AppImage + deb + المثبّتان): https://github.com/spos-systems/downloads/releases/tag/linux-v1.17.96
- البصمات: [SHA256SUMS.txt](https://github.com/spos-systems/downloads/releases/download/windows-v1.17.96/SHA256SUMS.txt) · [SHA256SUMS-Linux.txt](https://github.com/spos-systems/downloads/releases/download/linux-v1.17.96/SHA256SUMS-Linux.txt) · [SHA256SUMS-Android.txt](https://github.com/spos-systems/downloads/releases/download/android-v1.17.96/SHA256SUMS-Android.txt)

### v1.17.95 — درع هوية النشاط التجريبي + إصلاح المنفذ والتخزين
- ويندوز: https://github.com/spos-systems/downloads/releases/download/windows-v1.17.95/SPOS-Solah-Cloud-Windows-x64.zip
- ويندوز (المُطلِق): https://github.com/spos-systems/downloads/releases/download/windows-v1.17.95/SPOS-Solah-Cloud-Setup.exe
- لينكس: https://github.com/spos-systems/downloads/releases/download/linux-v1.17.95/SPOS-Solah-Cloud-Linux-x64.zip
- البصمات: [SHA256SUMS.txt](https://github.com/spos-systems/downloads/releases/download/windows-v1.17.95/SHA256SUMS.txt) · [SHA256SUMS-Linux.txt](https://github.com/spos-systems/downloads/releases/download/linux-v1.17.95/SHA256SUMS-Linux.txt)

## التحقق من الحزم

```bash
sha256sum -c SHA256SUMS-Linux.txt      # لينكس
sha256sum -c SHA256SUMS-Android.txt    # أندرويد
certutil -hashfile SPOS-Solah-Cloud-Windows-x64.zip SHA256   # ويندوز
```

> **ملاحظة الخادم (للمالك):** ⚠️ v1.17.106 يمس **الخادم نفسه** — حارس الدخول والإبطال اللحظي (إغلاق ثغرة المنتهي) + مسار `/api/owner/analytics` (تحليلات التفعيل) + رموز QR السائلة: **أعد نشر حاوية الخادم (Docker) من main في `pos-cloud-platform` بهذا الإصدار** — إغلاق الثغرة يسري فوراً على كل النسخ المثبتة (الويب والكمبيوتر والهاتف معاً) والتحليلات تظهر في لوحتك من الويب مباشرة. (v1.17.100 السابق: لا تغييرات خادمية — كل الإصلاحات في التطبيقات.)
