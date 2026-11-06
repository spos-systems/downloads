# تنزيلات منظومة صولة السحابية SPOS Solah Cloud

مستودع التوزيع الرسمي — كل حزم المنصات تُنشر هنا وتُقدَّم تلقائياً عبر قنوات التحديث في التطبيق.

## الروابط الدائمة (آخر ريليز كامل)

| المنصة | الرابط |
| --- | --- |
| ويندوز (المُطلِق) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Setup.exe |
| ويندوز (حزمة x64) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Windows-x64.zip |
| لينكس (المثبّت) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Setup-linux-x64.run |
| لينكس (حزمة x64) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Linux-x64.zip |
| أندرويد (APK) | https://github.com/spos-systems/downloads/releases/latest/download/SPOS-Solah-Cloud-Android.apk |

## رقع المنصات المستقلة (T291 — تصل عملاء المنصة فقط دون بقية المنصات)

### v1.17.96 — القفل الدائم للهوية + نافذة منتج ثابتة + مسح بلا كاميرا + باركود Code128 حقيقي
- ويندوز: https://github.com/spos-systems/downloads/releases/download/windows-v1.17.96/SPOS-Solah-Cloud-Windows-x64.zip
- ويندوز (المُطلِق): https://github.com/spos-systems/downloads/releases/download/windows-v1.17.96/SPOS-Solah-Cloud-Setup.exe
- لينكس: https://github.com/spos-systems/downloads/releases/download/linux-v1.17.96/SPOS-Solah-Cloud-Linux-x64.zip
- البصمات: [SHA256SUMS.txt](https://github.com/spos-systems/downloads/releases/download/windows-v1.17.96/SHA256SUMS.txt) · [SHA256SUMS-Linux.txt](https://github.com/spos-systems/downloads/releases/download/linux-v1.17.96/SHA256SUMS-Linux.txt)
- سجل التغيير الكامل والخادم: https://github.com/spos-systems/pos-cloud-platform/releases/tag/v1.17.96

### v1.17.95 — درع هوية النشاط التجريبي + إصلاح المنفذ والتخزين
- ويندوز: https://github.com/spos-systems/downloads/releases/download/windows-v1.17.95/SPOS-Solah-Cloud-Windows-x64.zip
- ويندوز (المُطلِق): https://github.com/spos-systems/downloads/releases/download/windows-v1.17.95/SPOS-Solah-Cloud-Setup.exe
- لينكس: https://github.com/spos-systems/downloads/releases/download/linux-v1.17.95/SPOS-Solah-Cloud-Linux-x64.zip
- البصمات: [SHA256SUMS.txt](https://github.com/spos-systems/downloads/releases/download/windows-v1.17.95/SHA256SUMS.txt) · [SHA256SUMS-Linux.txt](https://github.com/spos-systems/downloads/releases/download/linux-v1.17.95/SHA256SUMS-Linux.txt)

## التحقق من الحزم

```bash
sha256sum -c SHA256SUMS-Linux.txt   # لينكس
certutil -hashfile SPOS-Solah-Cloud-Windows-x64.zip SHA256   # ويندوز
```
