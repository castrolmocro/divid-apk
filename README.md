<div align="center">

<img src="https://img.shields.io/badge/DAVID%20V1-Android%20App-0A84FF?style=for-the-badge&logo=android&logoColor=white" height="36"/>

# DAVID V1 — DjamelBot Android

**لوحة تحكم احترافية لبوت فيسبوك ماسنجر — تطبيق Android بتصميم iOS 26**

---

## ⬇️ تحميل التطبيق

[![تحميل APK](https://img.shields.io/github/v/release/castrolmocro/divid-apk?label=%E2%AC%87%EF%B8%8F%20%D8%AA%D8%AD%D9%85%D9%8A%D9%84%20DAVID%20V1%20APK&style=for-the-badge&color=32D74B&logo=android)](https://github.com/castrolmocro/divid-apk/releases/latest/download/david-v1.apk)

> انقر الزر الأخضر أعلاه لتحميل أحدث نسخة مباشرةً

[![آخر إصدار](https://img.shields.io/github/v/release/castrolmocro/divid-apk?style=flat-square&label=آخر%20إصدار&color=0A84FF)](https://github.com/castrolmocro/divid-apk/releases/latest)
[![حالة البناء](https://img.shields.io/github/actions/workflow/status/castrolmocro/divid-apk/build-apk.yml?style=flat-square&label=حالة%20البناء)](https://github.com/castrolmocro/divid-apk/actions)

</div>

---

## ✨ الميزات

| الميزة | التفاصيل |
|--------|----------|
| 📱 تصميم iOS 26 | واجهة داكنة أنيقة مع قائمة جانبية |
| 🤖 ملفات شخصية متعددة | تبديل بين عدة بوتات بنقرة واحدة |
| 💬 مسنجر حي | إرسال رسائل وصور وصوت مع الردّ على الرسائل |
| 📡 الهاتف كسيرفر | تشغيل البوت من الهاتف عبر Termux + ngrok |
| ⚡ WakeLock | حماية من إيقاف ColorOS للخلفية |
| 🔋 استثناء البطارية | إعدادات OPPO/ColorOS 16 خطوة بخطوة |
| ✏️ تغيير الكنية | تغيير اسم البوت في كل الغروبات دفعةً واحدة |
| 🤖 ذكاء اصطناعي | دعم Claude AI |
| 📊 إحصائيات | لوحة تحكم كاملة مع سجل مباشر |

---

## 📲 خطوات التثبيت

### على OPPO K12S 5G / ColorOS 16

1. **حمّل** ملف APK من الزر أعلاه
2. **الإعدادات** ← **الأمان** ← **تثبيت تطبيقات من مصادر أخرى** ← فعّل للمتصفح
3. **افتح** ملف APK من مجلد التنزيلات وثبّت
4. **شغّل** التطبيق ← اضغط ⚙️ ← أدخل رابط السيرفر
5. كلمة السر الافتراضية: **`david2025`**

### تغيير كلمة السر
في ملف `config.json`:
```json
{
  "dashboard": {
    "password": "كلمة_السر_الجديدة"
  }
}
```

---

## 📡 الهاتف كسيرفر (Termux)

```bash
# تثبيت Node.js
pkg update && pkg install nodejs git -y

# تشغيل البوت
cd /sdcard/DAVID-V1
node index.js
```

ثم في التطبيق: القائمة الجانبية ← 📡 الهاتف كسيرفر ← **🔒 تفعيل WakeLock**

---

## 🔧 روابط السيرفر الشائعة

| النوع | الرابط |
|-------|--------|
| Railway | `https://اسمك.railway.app` |
| Render | `https://اسمك.onrender.com` |
| Termux نفس الشبكة | `http://192.168.x.x:5000` |
| Termux نفس الهاتف | `http://localhost:5000` |
| ngrok | `https://xxxx.ngrok-free.app` |

---

<div align="center">

صُنع بـ ❤️ | نسخة v4.0

</div>
