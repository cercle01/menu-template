# CIRCLE01 Digital Menu Template

## الملفات

- `index.html` — القالب الرئيسي، لا تحتاج لتعديله لكل عميل.
- `menu-data.json` — كل بيانات المطعم والمنيو والألوان.
- `images/logo.png` — شعار المطعم.
- `images/product-01.jpg`, `product-02.jpg` ... — صور المنتجات.

## إضافة عميل جديد

1. انسخ المستودع.
2. استبدل `images/logo.png` بشعار العميل.
3. عدّل `menu-data.json`.
4. ارفع صور المنتجات داخل `images/`.
5. انشر GitHub Pages.
6. استخدم رابط الموقع لإنشاء QR.

## تعديل الألوان

داخل `menu-data.json`:

```json
"theme": {
  "background": "#f4ebdc",
  "text": "#0b0705",
  "accent": "#9e5521",
  "muted": "#6e655c"
}
```

## إضافة منتج

```json
{
  "name": {
    "ar": "اسم المنتج",
    "en": "Product Name"
  },
  "price": 5000,
  "image": "images/product-05.jpg"
}
```
