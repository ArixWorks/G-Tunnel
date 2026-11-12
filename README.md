<img src="banner.svg" alt="G-Tunnel Banner" width="100%"/>

# 🚀 G-Tunnel — High-Performance WebSocket Proxy

[![Platform](https://img.shields.io/badge/Platform-GitHub%20Codespaces-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/features/codespaces)
[![Protocol](https://img.shields.io/badge/Protocol-VLESS%20%2B%20WS%20%2B%20TLS-00d9ff?style=flat-square&logo=v2ray&logoColor=white)](#)
[![Core](https://img.shields.io/badge/Core-Xray--core-7a00ff?style=flat-square&logo=xray&logoColor=white)](https://github.com/XTLS/Xray-core)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Auto](https://img.shields.io/badge/Setup-Fully%20Automated-brightgreen?style=flat-square&logo=githubactions&logoColor=white)](#)

## 🌍 English

**G-Tunnel** turns a free GitHub Codespace into a fully automated VLESS/WebSocket proxy powered by Xray-core.

- **Zero config:** fork the repo, create a Codespace, and ready-to-import VLESS links appear in your terminal in about 3 minutes.
- **Fresh UUID on every run** with WebSocket transport, built for unstable or censored networks.
- **Low latency:** 190–400 ms via 7 direct IPs plus a GitHub domain fallback.
- **Free:** runs inside your normal Codespaces quota (60 h/month, 90 h for students).
- Works with v2rayNG, Nekobox, v2rayN, Nekoray, V2Box, Streisand, FoXray.

> 📖 The full setup guide is in the Persian section below.

---

به **G-Tunnel** خوش آمدید؛ نسل جدید و بهینه‌سازی شده پروکسی‌های مبتنی بر GitHub Codespaces. این پروژه با هدف ارائه اتصالی پایدار، سریع و کاملاً خودکار، بر پایه هسته قدرتمند Xray و پروتکل WebSocket بازطراحی شده است.

---

## 🌟 چرا G-Tunnel؟

در نسخه **G-Tunnel**، ما تمامی موانع فنی را از پیش پای شما برداشته‌ایم. برخلاف نسخه‌های قدیمی که نیاز به ویرایش دستی فایل‌ها و ساخت UUID داشتند، در این پروژه همه‌چیز به صورت داینامیک و در لحظه اجرا (Runtime) انجام می‌شود.

| ویژگی | توضیح |
|---|---|
| **⚡ پینگ پایین** | کاهش از ۱۵۰۰ms به **۱۹۰–۴۰۰ms** با IP‌های اختصاصی |
| **🔗 اتصال پایدار** | پروتکل **WebSocket** برای محیط‌های دارای اختلال |
| **🤖 اتوماسیون ۱۰۰٪** | بدون نیاز به ویرایش دستی `config.json` |
| **🛡️ UUID یکتا** | هر بار اجرا یک UUID جدید — امنیت بیشتر |
| **📡 چند IP** | ۷ آدرس مستقیم + دامنه GitHub برای انتخاب بهترین پینگ |

---

## 🛠️ راهنمای نصب و اجرای سریع

برای راه‌اندازی **G-Tunnel** تنها کافیست مراحل زیر را دنبال کنید:

**۱. Fork کردن پروژه**
> در بالای صفحه روی گزینه **Fork** کلیک کنید تا یک نسخه از پروژه در حساب شما کپی شود.

**۲. ساخت Codespace**
> - وارد ریپوی فورک شده خود شوید
> - روی دکمه سبز **`<> Code`** کلیک کنید
> - در تب **Codespaces** گزینه **Create codespace on main** را انتخاب کنید

**۳. دریافت کانفیگ**
> - منتظر بمانید تا محیط اجرا آماده شود (حدود ۳ دقیقه)
> - به محض اتمام نصب، تمام لینک‌های **VLESS** به صورت خودکار در Terminal نمایش داده می‌شوند

---

## ⚙️ تنظیمات حیاتی برای عملکرد پایدار

### ۱. 🕐 تنظیم Idle Timeout

به [github.com/settings/codespaces](https://github.com/settings/codespaces) بروید:

- بخش **Default idle timeout** را پیدا کنید
- مقدار را به **`240`** دقیقه تغییر دهید و **Save** کنید

### ۲. 🌍 انتخاب Region

در همان صفحه تنظیمات، در بخش **Region**:

- گزینه **Set manually** را انتخاب کنید
- نزدیک‌ترین لوکیشن به ایران (مناطق اروپایی) را انتخاب کنید

---

## 📈 ظرفیت و محدودیت‌های زمانی

| نوع اکانت | سهمیه ماهانه |
|---|---|
| 👤 **اکانت عادی** | ۶۰ ساعت در ماه |
| 🎓 **اکانت دانشجویی** | ۹۰ ساعت در ماه |

> 💡 **نکته حرفه‌ای:** وقتی از پروکسی استفاده نمی‌کنید، از [پنل مدیریت](https://github.com/codespaces) سرور را **Stop** کنید تا سهمیه بیهوده مصرف نشود.

---

## 📱 نرم‌افزارهای پیشنهادی

| پلتفرم | نرم‌افزار |
|---|---|
| 🤖 **Android** | v2rayNG, Nekobox |
| 🪟 **Windows** | v2rayN, Nekoray |
| 🍎 **iOS** | V2Box, Streisand, FoXray |

---

## ⭐ حمایت از G-Tunnel

اگر این پروژه به شما کمک کرد، با یک **Star ⭐** در بالای صفحه ما را دلگرم کنید.

**🪙 حمایت مالی (Crypto Donates):**

| شبکه | آدرس |
|---|---|
| 💛 **USDT (BEP20)** | `0xec6b356e1b458564de16d01108cc391d8792a92a` |
| 🟢 **USDT (TRC20)** | `TSGuHweHCv1Y348Kwyvz5ANGdGNUykgx3c` |
| 💎 **TON** | `UQACY3kYWw28tsKV6PcXZrvneFfGGfMBnmeeM1wlopC1RNVh` |

---

<div align="center">

*توسعه داده شده با ❤️ برای آزادی دسترسی به اطلاعات*

</div>