<div align="center" dir="rtl">

# 🔧 Find & Replace هوشمند

### ابزار پیشرفته‌ی جستجو و جایگزینی در مرورگر — با Regex، دستورات DSL و هدف‌گیری ساختاری

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Vanilla JS](https://img.shields.io/badge/Vanilla-JS-f7df1e?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen.svg)]()
[![RTL Support](https://img.shields.io/badge/RTL-✓-blue.svg)]()
[![Tests](https://img.shields.io/badge/Tests-150%2B-success.svg)]()

<img src="https://raw.githubusercontent.com/USERNAME/smart-find-replace/main/preview.png" alt="Smart Find & Replace Preview" width="800">

</div>

---

<div dir="rtl">

## 📖 معرفی

**Find & Replace هوشمند** یک ابزار تحت وب و کاملاً آفلاین است که برای توسعه‌دهندگان، ویرایشگران کد، و هر کسی که با فایل‌های متنی، HTML، CSS یا JavaScript کار می‌کند، طراحی شده است.

برخلاف ابزارهای ساده‌ی Find & Replace، این پروژه از **Regex پیشرفته**، **دستورات DSL**، **هدف‌گیری ساختاری** (بر اساس نام کلاس، متد، یا المان)، و **نادیده‌گرفتن هوشمند تورفتگی** پشتیبانی می‌کند.

> 🚫 **بدون هیچ وابستگی (Zero Dependencies)** — فقط Vanilla JavaScript، HTML و CSS
> 🔒 **کاملاً آفلاین** — هیچ داده‌ای به سرور ارسال نمی‌شود

---

## ✨ ویژگی‌های کلیدی

<table>
<tr>
<td width="50%" valign="top">

### 🔍 جستجو و جایگزینی
- پشتیبانی کامل از **Regex** با گروه‌ها
- جایگزینی با `$1`, `$&`, `` $` ``, `$'`, `$$`
- پرچم‌های `i`, `s`, `g`, `m` و `u`
- حالت **حساس/غیرحساس** به بزرگی و کوچکی
- حالت **چندخطی (dotall)**

### 🎯 هدف‌گیری ساختاری
- `IN_CLASS` — جستجو داخل یک کلاس
- `IN_FUNCTION` — جستجو داخل یک متد
- `IN_SELECTOR` — جستجو داخل یک المان
- `IN` — مسیر چندسطحی (`class:App > function:init`)
- پشتیبانی از private class fields (`#priv`)

### ⇥ نادیده‌گرفتن تورفتگی
- Fallback خودکار برای match کردن متون با تورفتگی متفاوت
- پشتیبانی از **tab**، **space** و ترکیب آن‌ها
- کاملاً قابل تنظیم از پنل تنظیمات

### 📝 دو حالت ورودی دستورات
- **JSON** — ساختاریافته و قابل برنامه‌نویسی
- **DSL** — خوانا، ساده و مناسب برای نوشتن سریع

</td>
<td width="50%" valign="top">

### 📊 نمایش تفاوت‌ها (Diff)
- الگوریتم **LCS** برای پیدا کردن تفاوت دقیق
- نمایش کنار هم (قبل / بعد)
- هایلایت خطوط اضافه‌شده و حذف‌شده
- شماره‌گذاری خطوط اصلی

### ▶️ پیش‌نمایش زنده
- اجرای کد HTML/CSS/JS در iframe امن
- **Console Capture** برای نمایش `console.log`, `console.warn`, `console.error`
- تشخیص خطاهای runtime
- اجرای تست‌های خودکار

### 💾 مدیریت اسنیپت‌ها
- ذخیره‌ی دستورات پرتکرار
- بارگذاری سریع در `localStorage`
- حذف/جایگزینی آسان

### 🎨 UI/UX حرفه‌ای
- طراحی دارک مدرن
- پشتیبانی کامل از **RTL** (فارسی)
- Responsive برای موبایل
- Keyboard Shortcuts کامل
- Toast Notifications
- Highlighting با **Prism.js**

</td>
</tr>
</table>

---

## 🚀 شروع سریع

### نصب

هیچ نصبی نیاز نیست! فقط فایل را باز کنید:

```bash
# ۱. کلون کردن
git clone https://github.com/USERNAME/smart-find-replace.git

# ۲. ورود به پوشه
cd smart-find-replace

# ۳. باز کردن در مرورگر
open index.html
# یا
# فقط فایل index.html را در مرورگر بکشید و رها کنید
