# 🦇 Batman Panel — KataBump Edition

<p align="center">
  <b>🚀 Secure Multi-Protocol Connection Management Panel</b>
</p>

<p align="center">
  <b>A lightweight Batman Panel edition adapted for Node.js hosting on KataBump.</b>
</p>

<p align="center">

![Node.js](https://img.shields.io/badge/Node.js-18%2B-339933?style=for-the-badge\&logo=node.js)

![Express](https://img.shields.io/badge/Express-4.x-000000?style=for-the-badge\&logo=express)

![KataBump](https://img.shields.io/badge/KataBump-Ready-orange?style=for-the-badge)

![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</p>

---

# 🌐 About | درباره پروژه

## 🇬🇧 English

**Batman Panel — KataBump Edition** is a Node.js-based version of Batman Panel designed to run in a **KataBump Node.js environment**.

The project provides a web-based management panel with support for multi-protocol connection management, live server information, quotas, subscriptions and backup-related functionality.

The repository is intentionally simple and contains the main application in a single JavaScript entry point:

```text
index.js
```

The project uses:

```text
Node.js 18+
Express
Axios
```

and can be started with:

```bash
npm start
```

The official `package.json` defines Node.js `>=18` and uses Express `4.21.x` and Axios `1.7.x`.

---

## 🇮🇷 فارسی

**Batman Panel — KataBump Edition** نسخه‌ای از Batman Panel است که برای اجرا در محیط **Node.js سرویس KataBump** آماده شده است.

این پروژه یک پنل مدیریت تحت وب برای مدیریت ارتباطات چندپروتکلی، مشاهده اطلاعات سرور، مدیریت Quota، اشتراک‌ها و قابلیت‌های مربوط به Backup است.

ساختار پروژه بسیار ساده است و هسته اصلی برنامه در فایل:

```text
index.js
```

قرار دارد.

پروژه به:

```text
Node.js 18+
Express
Axios
```

نیاز دارد و با دستور زیر اجرا می‌شود:

```bash
npm start
```

طبق `package.json`، نسخه موردنیاز Node.js حداقل **18** است و پروژه از Express و Axios استفاده می‌کند.

---

# ✨ Features | امکانات

### 🖥️ Management Panel

* Web-based management interface
* Multi-protocol connection management
* Live server information
* Quota management
* Subscription management
* Backup-related functionality
* Server monitoring

### ⚡ Node.js

* Node.js 18+
* Express web server
* Axios HTTP client
* Simple `npm start` startup
* Minimal project structure

### ☁️ KataBump Ready

* Designed for Node.js hosting
* Suitable for KataBump environments
* No traditional VPS installation required for the KataBump deployment
* Simple upload / install / start workflow

---

# 🧩 Technology Stack | تکنولوژی پروژه

```text
┌─────────────────────────────┐
│       Batman Panel          │
├─────────────────────────────┤
│        Node.js 18+          │
├─────────────────────────────┤
│          Express            │
├─────────────────────────────┤
│           Axios             │
└─────────────────────────────┘
```

The repository's `package.json` defines the following dependencies:

```json
{
  "express": "^4.21.0",
  "axios": "^1.7.7"
}
```

---

# ☁️ Why KataBump?

## 🇬🇧 English

KataBump provides a convenient environment for running Node.js applications without requiring you to manage a traditional VPS yourself.

For this project, the basic deployment flow is:

```text
GitHub Repository
       ↓
KataBump Node.js Server
       ↓
npm install
       ↓
npm start
       ↓
Batman Panel
```

---

## 🇮🇷 فارسی

KataBump محیط مناسبی برای اجرای پروژه‌های Node.js فراهم می‌کند و برای این پروژه لازم نیست یک VPS سنتی را به‌صورت جداگانه مدیریت کنید.

روند کلی نصب:

```text
GitHub Repository
       ↓
KataBump Node.js Server
       ↓
npm install
       ↓
npm start
       ↓
Batman Panel
```

---

# 🚀 Installation | نصب

## 1️⃣ Create a KataBump Server

ابتدا در KataBump یک Server جدید ایجاد کنید.

محیط پروژه را روی:

```text
Node.js
```

قرار دهید.

برای اجرای این Repository حداقل:

```text
Node.js 18+
```

لازم است.

---

# 2️⃣ Download the Project | دریافت پروژه

می‌توانید Repository را Clone کنید:

```bash
git clone https://github.com/Batman-panel/Batman-Panel-Kata.git
```

سپس وارد پوشه پروژه شوید:

```bash
cd Batman-Panel-Kata
```

یا فایل‌های Repository را مستقیماً داخل محیط KataBump آپلود کنید.

ساختار اصلی:

```text
Batman-Panel-Kata/
│
├── index.js
└── package.json
```

Repository فعلی شامل همین دو فایل اصلی است.

---

# 3️⃣ Install Dependencies | نصب وابستگی‌ها

داخل Console سرور KataBump اجرا کنید:

```bash
npm install
```

این دستور dependencyهای پروژه را نصب می‌کند.

وابستگی‌های اصلی:

```text
express
axios
```

هستند.

---

# 4️⃣ Start Batman Panel | اجرای پنل

بعد از نصب dependencyها:

```bash
npm start
```

طبق `package.json`، دستور `npm start` مستقیماً این فایل را اجرا می‌کند:

```bash
node index.js
```

---

# 5️⃣ Open the Panel | ورود به پنل

بعد از اینکه برنامه با موفقیت اجرا شد، وضعیت Server را در KataBump بررسی کنید.

در صورتی که برنامه روی پورت عمومی تنظیم شده باشد، از آدرس عمومی ارائه‌شده توسط KataBump برای دسترسی به پنل استفاده کنید.

```text
https://YOUR-KATABUMP-ADDRESS
```

> پورت و آدرس عمومی را از تنظیمات همان Server در KataBump دریافت کنید.

---

# ⚙️ Project Configuration | تنظیمات پروژه

پروژه از Node.js و Express برای اجرای Web Application استفاده می‌کند.

ساختار اصلی:

```text
package.json
      │
      ▼
npm start
      │
      ▼
node index.js
      │
      ▼
Express Application
      │
      ▼
Batman Panel
```

---

# 📦 package.json

نسخه فعلی پروژه:

```json
{
  "name": "batman-panel",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "engines": {
    "node": ">=18"
  }
}
```

Dependencyهای اصلی:

```text
Express 4.21.x
Axios 1.7.x
```

---

# 🛠️ Quick Start | نصب سریع

اگر قبلاً یک Node.js Server در KataBump ساخته‌اید:

```bash
git clone https://github.com/Batman-panel/Batman-Panel-Kata.git
cd Batman-Panel-Kata
npm install
npm start
```

پس از اجرای موفق:

```text
Batman Panel
     ↓
Running
     ↓
KataBump Public Address
     ↓
Web Panel
```

---

# 📁 Project Structure | ساختار پروژه

```text
Batman-Panel-Kata/
│
├── index.js        # Main application
│
└── package.json    # Node.js configuration & dependencies
```

Repository فعلی عمداً ساختار ساده‌ای دارد و هسته برنامه در `index.js` قرار گرفته است.

---

# 🔄 Updating | بروزرسانی

برای بروزرسانی:

```bash
git pull
npm install
npm start
```

اگر Server در حال اجرا است، ابتدا آن را متوقف کنید و سپس نسخه جدید را اجرا کنید.

---

# 🧪 Development

برای اجرای محلی:

```bash
git clone https://github.com/Batman-panel/Batman-Panel-Kata.git
cd Batman-Panel-Kata
npm install
npm start
```

نیازمندی:

```text
Node.js >= 18
```

---

# 🦇 How It Works | نحوه کار

```text
                    ┌─────────────────┐
                    │     User        │
                    │    Browser      │
                    └────────┬────────┘
                             │
                             ▼
                  ┌─────────────────────┐
                  │      KataBump       │
                  │    Node.js Server   │
                  └──────────┬──────────┘
                             │
                             ▼
                  ┌─────────────────────┐
                  │      index.js       │
                  │   Batman Panel      │
                  └──────────┬──────────┘
                             │
                  ┌──────────┴──────────┐
                  ▼                     ▼
             ┌─────────┐          ┌─────────┐
             │ Express │          │  Axios  │
             └─────────┘          └─────────┘
```

---

# ⚠️ Important Notes | نکات مهم

### Node.js Version

این پروژه به Node.js نسخه **18 یا بالاتر** نیاز دارد.

### KataBump Resources

منابع هر Server به Plan و محدودیت‌های فعلی KataBump بستگی دارد.

برای پروژه‌های سنگین، قبل از استفاده طولانی‌مدت، محدودیت‌های منابع و قوانین سرویس را بررسی کنید.

### Public Port

برای اینکه پنل از اینترنت قابل دسترسی باشد، باید Port مورد استفاده برنامه با Port عمومی ارائه‌شده توسط محیط KataBump هماهنگ باشد.

---

# 🆓 Free / Low-Cost Deployment

این Repository برای اجرا در محیط Node.js طراحی شده و می‌توان آن را روی پلن‌های مناسب KataBump اجرا کرد.

اگر از Free Tier استفاده می‌کنید، محدودیت‌های همان پلن روی منابع، مدت فعال‌بودن Server و میزان استفاده اعمال می‌شود.

بنابراین:

> **The project is free/open-source; hosting availability and limits depend on the KataBump plan you use.**

---

# 🔗 Repository

**GitHub:**

https://github.com/Batman-panel/Batman-Panel-Kata

---

# ⭐ Support the Project

اگر Batman Panel برای شما مفید بود، با دادن یک ⭐ به Repository از پروژه حمایت کنید.

هر Star باعث می‌شود پروژه بیشتر دیده شود و توسعه آن ادامه پیدا کند.

---

# 🦇 Batman Panel

<p align="center">
  <b>Simple • Lightweight • Node.js • KataBump Ready</b>
</p>

<p align="center">
  <b>ساده • سبک • Node.js • آماده اجرا روی KataBump</b>
</p>

<p align="center">
  🦇 <b>Batman Panel</b> × <b>KataBump</b>
</p>
