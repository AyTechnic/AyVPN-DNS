<p align="center">
  <img src="https://ayvps.s3.ir-thr-at1.arvanstorage.ir/AyVPN-DNS/Win/Files/logo.png" alt="AyVPN-DNS Logo" width="120" onerror="this.onerror=null; this.src='https://img.shields.io/badge/Logo-AyVPN--DNS-00d4ff?style=for-the-badge';">
</p>

<h1 align="center">AyVPN-DNS</h1>

<p align="center">
  <strong>یک کلاینت حرفه‌ای VPN با قابلیت تونل‌زنی DNS و مدیریت هوشمند ریزالورها</strong>
</p>

<p align="center">
  <a href="https://github.com/AyTechnic/AyVPN-DNS" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-AyTechnic-181717?style=flat-square&logo=github" alt="GitHub">
  </a>
  <a href="https://t.me/AyVPN_DNS" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-@AyVPN_DNS-26A5E4?style=flat-square&logo=telegram" alt="Telegram">
  </a>
  <a href="https://shammay.ir" target="_blank">
    <img src="https://img.shields.io/badge/Website-shammay.ir-00d4ff?style=flat-square&logo=google-chrome" alt="Website">
  </a>
  <br>
  <img src="https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/Platform-Windows-blue?style=flat-square&logo=windows" alt="Platform">
  <img src="https://img.shields.io/badge/License-Proprietary-red?style=flat-square" alt="License">
</p>

---

## 🔰 معرفی برنامه (AyVPN-DNS)

**AyVPN-DNS** یک ابزار قدرتمند و پیشرفته برای ایجاد **تونل امن و سریع** با استفاده از پروتکل‌های DNS و SOCKS5 است. این برنامه با تکنیک‌های مدرنی مانند **MTU Discovery خودکار، متعادل‌سازی بار بین ریزالورها، پشتیبانی از ARQ برای کاهش از دست رفتن بسته، فشرده‌سازی ترافیک و قابلیت عبور از فیلترینگ هوشمند**، تجربه‌ای پایدار و پرسرعت را برای کاربران ویندوز فراهم می‌کند.

این برنامه حاصل تلاش تیم **AyTechnic** و توسعه‌دهنده ارشد **shammay** است و با الهام از نیاز به اتصالی امن و بدون قطعی طراحی شده است.

---

## ✨ قابلیت‌های کلیدی ویندوز

| دسته‌بندی | قابلیت |
| :--- | :--- |
| **⚙️ هسته و تونل** | ✅ تونل‌زنی مبتنی بر DNS با پشتیبانی از دامنه‌های سفارشی<br>✅ پروتکل SOCKS5 با قابلیت احراز هویت<br>✅ قابلیت DPI bypass و Fragment over DNS |
| **🧠 مدیریت ریزالور** | 🔄 تست MTU به صورت موازی روی ۴۴۳+ ریزالور<br>🎲 استراتژی‌های Round‑Robin، کمترین تاخیر، کمترین خطا<br>🔄 تشخیص خودکار و حذف ریزالورهای قطع شده<br>♻️ بررسی مجدد ریزالورهای غیرفعال در پس‌زمینه |
| **📦 قابلیت اطمینان** | 🔁 ارسال مجدد بسته‌ها (Packet Duplication)<br>📡 ARQ با پنجره لغزشی و RTO پویا<br>🛡️ بررسی خودکار تایم‌اوت سرورها و غیرفعال‌سازی موقت |
| **🚀 بهینه‌سازی** | 🗜️ فشرده‌سازی ترافیک با ZSTD، LZ4 یا ZLIB<br>📏 کشف خودکار MTU و ذخیره در فایل<br>🧵 پشتیبانی از پردازش موازی (RX/TX Workers و Tunnel Processors) |
| **🔒 امنیت** | 🔐 رمزنگاری با XOR، ChaCha20، AES‑128/192/256‑GCM<br>🗝️ کلید رمزنگاری پویا به همراه انکود بیس۶۴<br>👤 لاگین آنلاین / آفلاین با کش اطلاعات کاربر |
| **🎨 رابط کاربری** | 🌍 کره زمین چرخان با هاله رنگی و دایره موفقیت سبز<br>📊 نمایش تعداد ریزالورهای فعال به صورت لحظه‌ای<br>📜 نمایش لاگ‌های رنگی با دسته‌بندی (موفقیت، خطا، ریزالور، اتصال)<br>🔄 پشتیبانی از زبان فارسی و انگلیسی<br>🎨 ویجت شمای با حالت برق‌زننده و لینک به وب‌سایت |
| **🕹️ کنترل و سفارشی‌سازی** | 🚀 دکمه اتصال/قطع روی کره زمین<br>⚙️ تنظیمات پیشرفته شامل تنظیمات تونل، پروکسی، DNS محلی، ARQ، MTU، فشرده‌سازی<br>✏️ ویرایش دستی فایل ریزالورها<br>📡 بروزرسانی خودکار لیست ریزالورها از سرور |

---

## 🖼️ پیش‌نمایش رابط کاربری (وِب دمو)

برای آشنایی با فضای گرافیکی برنامه، می‌توانید نسخه تحت وب آن را که دقیقاً شبیه‌ساز نسخه ویندوز است، مشاهده کنید. این دمو امکاناتی مانند اتصال/قطع، چرخش کره، تولید لاگ‌های زنده و تغییر زبان را شبیه‌سازی می‌کند.

<div align="center">
  <a href="https://ayvps.s3.ir-thr-at1.arvanstorage.ir/AyVPN-DNS/www/AyVPN-DNS.html" target="_blank">
    <img src="https://ayvps.s3.ir-thr-at1.arvanstorage.ir/AyVPN-DNS/Win/Files/logo.png" alt="Live Demo Thumbnail" width="80%" style="border-radius: 16px; border: 1px solid #00d4ff;" onerror="this.onerror=null; this.src='https://via.placeholder.com/800x400?text=AyVPN-DNS+Demo';">
  </a>
</div>

<div align="center">
  <a href="https://ayvps.s3.ir-thr-at1.arvanstorage.ir/AyVPN-DNS/www/AyVPN-DNS.html" target="_blank">
    <img src="https://img.shields.io/badge/🌐-مشاهده دموی آنلاین-00d4ff?style=for-the-badge" alt="Live Demo">
  </a>
</div>

> **نکته:** در صورتی که تصویر پیش‌نمایش بارگذاری نشد، روی دکمه کلیک کنید تا دمو در مرورگر باز شود.

---

## 📥 دانلود و نصب (ویندوز)

برای دانلود جدیدترین نسخه برنامه (فایل اجرایی `exe`)، روی لینک زیر کلیک کنید:

<p align="center">
  <a href="https://ayvps.s3.ir-thr-at1.arvanstorage.ir/AyVPN-DNS/Win/AyVPN-DNS%201.0.0%20shammay.ir.exe" target="_blank">
    <img src="https://img.shields.io/badge/📥-دانلود_AyVPN--DNS_1.0.0-4caf50?style=for-the-badge&logo=windows" alt="Download">
  </a>
</p>

> **نکته نصب:** پس از دانلود، فایل را اجرا کنید. برنامه نیازی به نصب خاصی ندارد و به صورت پرتابل (Portable) اجرا می‌شود. برای اولین اجرا ممکن است هشدار SmartScreen ویندوز نمایش داده شود که کافی است روی **「اطلاعات بیشتر → اجرا به هر حال」** کلیک کنید.

---

## 🖥️ نحوه استفاده سریع

1. **اجرا:** فایل `AyVPN-DNS 1.0.0 shammay.ir.exe` را باز کنید.
2. **ورود:** در پنجره لاگین، نام کاربری خود را وارد کنید (مثلاً `shammay` یا `Aylin`). در صورت قطعی اینترنت، برنامه از اطلاعات آفلاین استفاده می‌کند.
3. **اتصال:** روی **🌍 کره زمین** که در وسط صفحه قرار دارد کلیک کنید. کره شروع به چرخش کرده و دایره سبز موفقیت ظاهر می‌شود.
4. **تنظیمات:** می‌توانید از پنل چپ برای تغییر دامنه‌ها، کلید رمزنگاری و IP/Port پروکسی استفاده کنید.
5. **ریزالورها:** با دکمه **「📋 لیست」** در پنل راست می‌توانید فایل ریزالورها را ویرایش کرده و با دکمه **「🔄 بروزرسانی」** آنها را از سرور دریافت کنید.
6. **فعال‌سازی پروکسی:** با کلیک روی دکمه **「Proxy OFF」** در پنل چپ، پروکسی سیستم به صورت خودکار روی `127.0.0.1:18000` تنظیم می‌شود.
7. **تغییر زبان:** با کلیک روی آیکون **「🌐 زبان」** در پنل راست، می‌توانید بین فارسی و انگلیسی جابجا شوید.

---

## 📄 ساختار فایل‌های برنامه

| نام فایل | توضیح |
| :--- | :--- |
| `client_config.toml` | فایل تنظیمات اصلی (پارامترهای تونل، MTU، ARQ، فشرده‌سازی، و ...) |
| `client_resolvers.txt` | لیست ریزالورهای DNS (هر خط یک IP:PORT) |
| `shammay` | فایل کش اطلاعات کاربر (شامل نام کاربری، حجم، تاریخ اولین ورود) |
| `AyVPN-DNS_success_test_*.log` | لاگ‌های دقیق تست MTU و کانکشن‌های موفق |

> تمام این فایل‌ها در حالت اجرای exe در مسیر `%APPDATA%\AyVPN-DNS\Client` ایجاد می‌شوند.

---

## 🛠️ تنظیمات پیشرفته (برخی از پارامترهای `client_config.toml`)

```toml
DOMAINS = ["shammay.ir"]
DATA_ENCRYPTION_METHOD = 1          # 0=none, 1=XOR, 2=ChaCha20, 3-5=AES-GCM
PROTOCOL_TYPE = "SOCKS5"
LISTEN_PORT = 18000
LOCAL_DNS_ENABLED = false
RESOLVER_BALANCING_STRATEGY = 2     # 2=Round-Robin
PACKET_DUPLICATION_COUNT = 2
ARQ_WINDOW_SIZE = 1000
MAX_UPLOAD_MTU = 190
MAX_DOWNLOAD_MTU = 990
UPLOAD_COMPRESSION_TYPE = 0         # 0=OFF, 1=ZSTD, 2=LZ4, 3=ZLIB
LOG_LEVEL = "INFO"
```

برای اعمال تغییرات، فایل TOML را با یک ویرایشگر متنی (مثل Notepad) ویرایش کرده و برنامه را مجدداً اجرا کنید.

---

## 📞 ارتباط با توسعه‌دهنده

- **وب‌سایت:** [shammay.ir](https://shammay.ir)
- **گیت‌هاب:** [AyTechnic/AyVPN-DNS](https://github.com/AyTechnic/AyVPN-DNS)
- **تلگرام:** [@AyVPN_DNS](https://t.me/AyVPN_DNS)

اگر باگی مشاهده کردید یا سوالی داشتید، از طریق لینک‌های بالا با ما در میان بگذارید.

---

<p align="center">
  <strong>AyVPN-DNS</strong> • ساخته شده با عشق توسط تیم <strong>AyTechnic</strong> و <strong>shammay</strong> • <strong>امن، پایدار، نامحدود</strong>
</p>





