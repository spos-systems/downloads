# تنزيلات منظومة صولة السحابية SPOS Solah Cloud

مستودع التوزيع الرسمي — كل حزم المنصات تُنشر هنا وتُقدَّم تلقائياً عبر قنوات التحديث في التطبيق.

## الروابط الدائمة (آخر ريليز كامل — v1.17.100)

| المنصة | الرابط |
| --- | --- |
| ويندوز (المُطلِق) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Setup.exe |
| ويندوز (حزمة x64) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Windows-x64.zip |
| لينكس (المثبّت الخفيف) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Setup-linux-x64.run |
| لينكس (المثبّت الكامل دون اتصال) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Setup-Offline-linux-x64.run |
| لينكس (حزمة x64) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Linux-x64.zip |
| أندرويد (APK) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Android.apk |

## v1.17.100 — الريليز الكامل (latest): إقلاع فوري بلا انتظار الشبكة

**التطبيق لم يعد ينتظر الإنترنت ليفتح** — كان إقلاع التطبيق ينتظر نداءً سحابياً بلا مهلة (وهو فحص لوحة مالك المنصّة لا يعني الكاشير أصلاً)، فمع واي فاي ضعيف يعلّق النداء وتظهر شاشة «تعذر الاتصال بالخدمة السحابية» وزر إعادة المحاولة، بينما إغلاق الواي فاي كلياً كان يدخل طبيعياً. من الآن:

- نافذة الدخول تفتح فور اكتمال التهيئة المحلية مهما كانت حالة الشبكة.
- مهلة افتراضية 20 ثانية لكل نداء سحابي — وزر «دخول» فاشل الشبكة يسقط خلال 12 ثانية لمسار الدخول بلا إنترنت (بيانات آخر دخول ناجح).
- عودة الإنترنت تجدد الجلسة والترخيص المحلي خلال ثوانٍ تلقائياً — النظام يعمل بلا إنترنت ثم يزامن.
- التخزين المحلي الذكي للترخيص (لقطة اشتراك + فترة سماح) كان موجوداً — الخلل كان في بوابة الإقلاع فقط.

يشمل الإصدار أيضاً إصلاحات التجربة الخمسة من v1.17.99 (كومبوهات طباعة مصممة + بطاقات طابعات جديدة + كلمة المرور لا تبقى في صفحة الدخول + بلا زر مشاركة + شريط التنقل بضغط الزر حصراً).

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

> **ملاحظة الخادم (للمالك):** لا تغييرات خادمية في v1.17.100 — كل الإصلاحات في التطبيقات ولا حاجة لأي سحب ولا ترحيلات قاعدة. (v1.17.96 السابق: تفعيل الرفض الخادمي للقفل الدائم وتحذيرات التدقيق [T333] يتطلب سحب main وإعادة بناء حاوية الخادم في `pos-cloud-platform`.)
