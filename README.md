<div align="center">

# MaxWorld for Windows

**کلاینت V2Ray / Xray برای ویندوز — سریع، زیبا و قدرتمند**  
**A fast, beautiful and complete Xray / V2Ray client for Windows**

![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-0078D6?logo=windows&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-33-47848F?logo=electron&logoColor=white)
![Core](https://img.shields.io/badge/core-Xray-1f6feb)
![Languages](https://img.shields.io/badge/languages-فارسی%20%7C%20English-orange)

[دانلود آخرین نسخه](../../releases/latest) · [Download latest](../../releases/latest)

</div>

---

## فارسی

### MaxWorld چیست؟
MaxWorld یک کلاینت VPN دسکتاپ برای ویندوز است که روی هسته **Xray** ساخته شده. ظاهر مدرن، عملکرد سریع و امکانات کامل برای مدیریت سرورها، اشتراک‌ها و حریم خصوصی.

### امکانات کلیدی

**اتصال و پروتکل‌ها**
- VLESS · VMess · Trojan · Shadowsocks · WireGuard · Hysteria2
- Reality / TLS · WebSocket · gRPC · HTTPUpgrade · XHTTP · KCP
- حالت پروکسی سیستم و حالت **TUN** (کل سیستم، با دسترسی ادمین)
- Fragment · Mux · انتخاب fingerprint

**مدیریت سرور و اشتراک**
- افزودن با لینک، کلیپ‌بورد، کشیدن و رها کردن، فایل JSON یا `.conf`
- اشتراک با نمایش حجم و روزهای باقی‌مانده + به‌روزرسانی خودکار
- تست پینگ همه سرورها، انتخاب سریع‌ترین، علاقه‌مندی و جستجو
- پینگ زنده، سرعت زنده دانلود/آپلود، نمودار، آی‌پی و کشور خروجی

**مسیریابی و حریم خصوصی**
- مسیریابی هوشمند: ایران / چین / روسیه مستقیم
- مسدودسازی تبلیغات و ردیاب‌ها (سپر با سه سطح)
- لیست‌های آماده + لیست دلخواه (hosts یا Adblock)
- DNS دلخواه و DNS over HTTPS
- قوانین دلخواه کاربر

**ظاهر و تجربه**
- ۸ پوسته زیبا + فارسی (راست‌به‌چپ) و انگلیسی
- سینی سیستم، اجرای خودکار با ویندوز، پشتیبان‌گیری و بازیابی
- رابط کاربری روان و مدرن با انیمیشن‌ها

### ساخت و نصب
1. از تب **Actions** ورک‌فلو «Build MaxWorld for Windows» را اجرا کن.
2. فایل‌های `MaxWorld-Setup-...exe` و `MaxWorld-Portable-...exe` را از Artifacts یا Releases بگیر.
3. نصب‌کننده را اجرا کن یا نسخه Portable را مستقیم اجرا کن.

> برای حالت TUN باید برنامه را با دسترسی Administrator اجرا کنی.

### ساختار پروژه
```
src/
  core/          منطق هسته، پارسر لینک، کانفیگ Xray، پروکسی سیستم
  main/          فرآیند اصلی Electron
  renderer/      رابط کاربری (HTML/CSS/JS)
test/            تست‌های خودکار
```

### سپاس
- [Xray-core](https://github.com/XTLS/Xray-core)
- [Electron](https://www.electronjs.org/)
- لیست‌های StevenBlack و AdGuard

---

## English

### What is MaxWorld?
MaxWorld is a desktop VPN client for Windows built on the **Xray** core. Modern UI, high performance, and full features for server & subscription management plus privacy tools.

### Key Features
- **Protocols:** VLESS, VMess, Trojan, Shadowsocks, WireGuard, Hysteria2 with Reality/TLS and multiple transports
- **Modes:** System proxy + full TUN mode (admin required)
- **Servers & subs:** Import from link / clipboard / drag-drop / JSON / WireGuard conf; data & expiry display; auto-update; ping tests; live speed & latency
- **Routing & privacy:** Smart routing (Iran/China/Russia direct), multi-level ad/tracker shield, custom lists, DoH, custom rules
- **UX:** 8 themes, Persian (RTL) + English, system tray, autostart, backup/restore

### Build & Install
Run the GitHub Actions workflow. Download the Setup or Portable exe from Artifacts / Releases.

### Credits
Xray-core, Electron, StevenBlack hosts, AdGuard filters.

---

Made with ❤️ by **MaxWorld**
