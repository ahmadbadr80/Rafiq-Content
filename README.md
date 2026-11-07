# Rafiq Content — محتوى رفيق

مستودع تنزيلات عامة لتطبيق **رفيق** المجاني.

## مصحف المدينة المنورة — حفص — الطبعة الخضراء 1441 هـ

[تحميل المصحف كاملًا — حوالي 65 ميجابايت](https://github.com/ahmadbadr80/Rafiq-Content/releases/download/mushaf-madinah-1441-v1/MushafMadinaHafsGreen1441.pdf)

[الإصدار وملف التحقق](https://github.com/ahmadbadr80/Rafiq-Content/releases/tag/mushaf-madinah-1441-v1)

- نفس الملف الأصلي دون تغيير المحتوى أو ترتيب الصفحات.
- الحجم الدقيق: **65,008,727 bytes**.
- بدون صوتيات، وبدون ملفات سورس التطبيق.
- المصدر: مصحف المدينة المنورة، مجمع الملك فهد؛ [النسخة المصورة في Internet Archive](https://archive.org/details/MushafMadinaHafsGreen1441).
- حقوق الطبعة محفوظة لأصحابها. هذا المستودع مرآة تنزيل وليس جهة الإصدار.

## Integrity and page mapping

SHA-256:

```text
2f0b03925568fca326f47a5ec756df2c3eecc8b29f75471f3a0815a5a3e58d28
```

The unchanged PDF contains 640 physical leaves. Printed Quran pages 1–604 map to
zero-based PDF leaf indexes 3–606. The release workflow checks the exact byte
count, SHA-256 and PDF header before publishing. The application also checks
the downloaded file and PDF page count before making it available offline.

A complete public download was independently checked against the pinned SHA-256
on 7 November 2026. Download speed depends on the network and location.

## Publishing

The workflow `.github/workflows/publish-mushaf.yml` can be run manually under
Actions. Existing published assets are verified, not overwritten.
The original Archive download gateway returned HTTP 500 during initial mirroring;
the workflow therefore uses the Archive storage server reported by the item's
metadata. All bytes must still match the pinned hash.
