# 🚀 دليل النشر على GitHub Pages

## الأوامر المطلوبة للنشر

### 1. إضافة الملفات الجديدة إلى Git

```bash
git add .
```

### 2. إنشاء commit جديد

```bash
git commit -m "Add GitHub Pages deployment configuration"
```

### 3. رفع التغييرات إلى GitHub

```bash
git push origin main
```

## ⚙️ إعداد GitHub Pages (مرة واحدة فقط)

### 1. اذهب إلى إعدادات الـ Repository

- اذهب إلى GitHub repository
- اضغط على تبويب **Settings**

### 2. تفعيل GitHub Pages

- في القائمة الجانبية، اضغط على **Pages**
- في قسم **Source**، اختر **GitHub Actions**
- احفظ الإعدادات

## 🔍 التحقق من النشر

### 1. مراقبة العملية

- اذهب إلى تبويب **Actions** في الـ repository
- ستجد workflow جديد يسمى "Deploy to GitHub Pages"
- انتظر حتى يكتمل (عادة 2-3 دقائق)

### 2. الوصول للموقع

- بعد اكتمال النشر، الموقع سيكون متاحاً على:

```
https://[username].github.io/ERP-Wireframes/
```

- استبدل `[username]` باسم المستخدم الخاص بك

## 📁 الملفات المضافة

تم إضافة الملفات التالية للنشر:

- ✅ `index.html` - الصفحة الرئيسية (نسخة من login_wireframe.html)
- ✅ `.nojekyll` - لتعطيل معالجة Jekyll
- ✅ `.github/workflows/deploy.yml` - workflow للنشر التلقائي
- ✅ `README.md` - تم تحديثه بمعلومات GitHub Pages

## 🔄 النشر المستقبلي

بعد الإعداد الأولي، كل ما عليك فعله هو:

```bash
git add .
git commit -m "Update wireframes"
git push origin main
```

وسيتم النشر تلقائياً! 🎉

## 🛠️ استكشاف الأخطاء

### إذا لم يعمل النشر:

1. تأكد من أن GitHub Actions مفعل
2. تحقق من تبويب **Actions** للأخطاء
3. تأكد من أن الـ repository public (أو أن لديك GitHub Pro)

### إذا لم تظهر الصفحة:

1. انتظر 5-10 دقائق (أحياناً يستغرق وقت أطول)
2. تأكد من صحة الرابط
3. تحقق من إعدادات Pages في Settings

## 📞 الدعم

إذا واجهت أي مشاكل، تحقق من:

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
