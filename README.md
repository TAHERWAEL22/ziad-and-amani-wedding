# 💍 دعوة زفاف زياد وأماني

دعوة زفاف تفاعلية بتصميم أنيق، مبنية بـ HTML و CSS و JavaScript خالص — جاهزة للنشر الفوري على Vercel.

---

## 📁 هيكل المشروع

```
invit/
├── wedding-invitation.html   ← صفحة الدعوة الرئيسية (نقطة الدخول)
├── wedding-song.mp3          ← ملف الموسيقى (يجب أن يكون في نفس المجلد)
├── vercel.json               ← إعدادات النشر على Vercel
├── .gitignore                ← ملفات مستثناة من Git
└── README.md                 ← هذا الملف
```

> **مهم:** ملف `wedding-song.mp3` يجب أن يكون موجوداً في نفس مجلد `wedding-invitation.html` حتى تعمل الموسيقى بشكل صحيح.

---

## 🚀 خطوات النشر على Vercel عبر GitHub

### 1. رفع المشروع على GitHub

```bash
# داخل مجلد المشروع
git init
git add .
git commit -m "initial commit: wedding invitation"

# أنشئ مستودعاً جديداً على github.com ثم اربطه
git remote add origin https://github.com/YOUR_USERNAME/wedding-invitation.git
git branch -M main
git push -u origin main
```

### 2. ربط المستودع بـ Vercel

1. افتح [vercel.com](https://vercel.com) وسجّل الدخول بحساب GitHub.
2. اضغط **Add New → Project**.
3. اختر المستودع `wedding-invitation` من القائمة.
4. اضغط **Deploy** مباشرةً — لا توجد إعدادات بناء مطلوبة (المشروع ثابت بالكامل).

بعد ثوانٍ ستحصل على رابط مباشر مثل:
```
https://wedding-invitation-xxxx.vercel.app
```

### 3. التحديث التلقائي

أي `git push` إلى الفرع `main` سيُطلق نشراً جديداً تلقائياً على Vercel.

---

## 🔗 رابط خرائط جوجل

في ملف `wedding-invitation.html`، ابحث عن السطر:

```html
href="https://maps.google.com/?q=قاعة+لاروز+دكرنس"
```

استبدل الرابط برابط المشاركة الحقيقي من خرائط جوجل للحصول على دقة أفضل في الموقع.

---

## ✨ المميزات

- 💌 ظرف تفاعلي مع ختم شمعي
- 🎵 موسيقى خلفية تنطلق عند فتح الدعوة
- ⏱️ عداد تنازلي حتى يوم الفرح
- 📍 زر الموقع على خرائط جوجل
- 📝 سجل تهاني الضيوف (محفوظ في المتصفح)
- 📱 تصميم متجاوب للجوال والحاسب
