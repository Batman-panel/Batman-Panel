# 🦇 Batman Panel

> A lightweight, modern multi-protocol connection management panel built with Node.js and Express.

[![Node.js](https://img.shields.io/badge/Node.js-18%2B-339933?style=for-the-badge\&logo=node.js\&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.x-000000?style=for-the-badge\&logo=express\&logoColor=white)](https://expressjs.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![KataBump](https://img.shields.io/badge/KataBump-Free%20Hosting-6C63FF?style=for-the-badge)](https://katabump.com/)

Batman Panel is a Node.js-based web panel focused on connection management, subscriptions, quotas, live server information, and backups.

It is designed to stay lightweight and can be deployed on a standard Linux VPS or on a free KataBump Node.js server.

---

## ✨ Features

* 🦇 **Batman-themed panel experience**
* 🔐 **Connection management**
* 🌐 **Multi-protocol configuration management**
* 📊 **Live server information and status**
* 📦 **Subscription management**
* 📈 **Quota / usage management**
* 💾 **Backup support**
* ⚡ **Lightweight Node.js + Express architecture**
* 📱 **Web-based interface**
* 🚀 **Easy deployment on Linux VPS**
* 🆓 **Compatible with KataBump's free Node.js hosting**

---

## 🧰 Tech Stack

| Technology  | Purpose              |
| ----------- | -------------------- |
| Node.js 18+ | Runtime              |
| Express 4   | Web server / backend |
| Axios       | HTTP requests        |
| JavaScript  | Application logic    |

The current project uses `index.js` as its main entry point and `npm start` to launch the application.

---

# 🚀 Installation

## 1. Clone the repository

```bash
git clone https://github.com/Batman-panel/Batman-Panel.git
cd Batman-Panel
```

## 2. Install dependencies

```bash
npm install
```

## 3. Start Batman Panel

```bash
npm start
```

The application will start through:

```text
node index.js
```

Use the port exposed by your hosting environment when opening the panel in your browser.

---

# 🆓 Deploy Batman Panel on KataBump

Batman Panel is compatible with KataBump's Node.js environment.

KataBump provides a free hosting plan for small Node.js applications, with automatic `npm install` support for projects containing a `package.json`.

### Step 1 — Create a Node.js server

Open:

```text
https://dashboard.katabump.com/
```

Create a new server and select **Node.js**.

For the runtime, use a supported LTS version such as **Node.js 18.x or 20.x**.

### Step 2 — Upload the project

You can upload the project files directly or import the repository.

The important files are:

```text
Batman-Panel/
├── index.js
├── package.json
├── README.md
└── Time Ultlimited.txt
```

### Step 3 — Configure the startup file

In the KataBump **Startup** settings, make sure the JavaScript entry point is:

```text
index.js
```

The project already contains:

```json
"scripts": {
  "start": "node index.js"
}
```

### Step 4 — Start the server

Open the **Console** and start the server.

KataBump automatically installs the dependencies from `package.json` on the first start.

After the application starts successfully, open the address/port exposed by your server.

> 💡 The free KataBump plan currently provides limited shared resources, so the free environment is best suited to lightweight deployments and testing.

---

# 📁 Project Structure

```text
Batman-Panel/
│
├── index.js
├── package.json
├── README.md
└── Time Ultlimited.txt
```

### `index.js`

Main application file containing the Batman Panel server and application logic.

### `package.json`

Project metadata, dependencies, Node.js requirement, and startup command.

### `Time Ultlimited.txt`

Contains additional deployment/renewal notes and an example of a KataBump renewal workflow.

---

# ⚙️ Requirements

### Minimum

* Node.js **18 or newer**
* npm
* Linux VPS or a compatible Node.js hosting environment

### For KataBump

* A KataBump account
* A Node.js server
* Batman Panel files
* `package.json` and `index.js` available in the project root

---

# 🔄 Updating the Panel

To update a local clone:

```bash
git pull
npm install
npm start
```

On KataBump, upload/sync the updated project files and restart the server.

---

# 🛠️ Troubleshooting

### `Cannot find module`

Run:

```bash
npm install
```

Then restart the application.

### Panel does not start

Check the console and verify:

```text
Node.js >= 18
Entry point = index.js
package.json = present
```

### Changes are not visible

Restart the Node.js server and refresh the browser cache.

### KataBump deployment does not start

Make sure `index.js` and `package.json` are located in the server's project root and that the startup configuration points to `index.js`.

---

# 🔐 Security Notes

* Never publish private credentials, passwords, tokens, or secrets in the repository.
* Keep administrative access protected.
* Do not expose sensitive configuration data in screenshots, logs, or public commits.
* Use environment variables or your hosting provider's secret-management features for private values when applicable.

---

# 📝 License

This project is released under the **MIT License**.

See the `LICENSE` file for details.

---

# 🌐 Links

**GitHub Repository**

https://github.com/Batman-panel/Batman-Panel

**KataBump**

https://katabump.com/

**KataBump Dashboard**

https://dashboard.katabump.com/

---

# 🇮🇷 فارسی

## 🦇 درباره Batman Panel

**Batman Panel** یک پنل وب سبک بر پایه Node.js و Express است که برای مدیریت ارتباط‌ها، اشتراک‌ها، سهمیه مصرف، اطلاعات زنده سرور و پشتیبان‌گیری طراحی شده است.

ساختار پروژه به‌گونه‌ای است که علاوه بر VPS لینوکسی معمولی، می‌توان آن را روی محیط Node.js سرویس **KataBump** نیز اجرا کرد.

### ⭐ امکانات

* 🦇 رابط کاربری با سبک Batman
* 🔐 مدیریت اتصال‌ها
* 🌐 مدیریت کانفیگ‌های چندپروتکله
* 📊 نمایش اطلاعات و وضعیت سرور
* 📦 مدیریت Subscription
* 📈 مدیریت Quota و مصرف
* 💾 پشتیبان‌گیری
* ⚡ حجم و وابستگی‌های نسبتاً سبک
* 🆓 امکان اجرای پروژه روی پلن رایگان KataBump

### 🚀 اجرای سریع

```bash
git clone https://github.com/Batman-panel/Batman-Panel.git
cd Batman-Panel
npm install
npm start
```

### 🆓 اجرای رایگان روی KataBump

در KataBump یک سرور **Node.js** بسازید، فایل‌های پروژه را آپلود یا از GitHub وارد کنید و فایل شروع را روی:

```text
index.js
```

قرار دهید.

سپس سرور را Start کنید تا وابستگی‌های `package.json` نصب شده و برنامه اجرا شود.

> ⚠️ منابع پلن رایگان محدود هستند و برای پروژه‌های سبک و تست مناسب‌ترند.

---

## ❤️ Support / Contributions

Issues, bug reports, feature requests, and pull requests are welcome.

Made with 🦇 by **Batman Panel**
