# Birinciler

مشروع ويب بواجهة عربية (RTL) لعرض وإدارة المنتجات أو المحتوى بشكل تفاعلي داخل صفحة واحدة.

## الملفات
- `index.html` — الملف الرئيسي.
- `birinciler-icon.png` — أيقونة التطبيق.
- `README.md` — هذا الملف.
- `manifest.json` — ملف تعريف التطبيق للمتصفح.

## التشغيل
1. ارفع الملفات إلى مستودع GitHub.
2. افتح `index.html` مباشرة أو فعّل GitHub Pages.
3. تأكد أن الأيقونة موجودة بنفس الاسم `birinciler-icon.png`.

## النشر على GitHub Pages
- افتح إعدادات المستودع.
- من قسم Pages اختر `Deploy from a branch`.
- اختر الفرع `main` والمجلد `/root`.
- احفظ وانتظر ظهور الرابط.

## ملاحظات مهمة
- إذا غيّرت اسم الأيقونة، عدّل السطر التالي داخل `index.html`:
  ```html
  <link rel="apple-touch-icon" href="birinciler-icon.png">
  ```
- من الأفضل أيضًا إضافة favicon وملف manifest لدعم أفضل على الجوال.

## هيكل المجلد
```txt
project/
├── index.html
├── birinciler-icon.png
├── manifest.json
└── README.md
```

## الترخيص
أضف الترخيص المناسب لمشروعك.
