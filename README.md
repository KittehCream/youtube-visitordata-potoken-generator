# 🎥 YouTube VisitorData & PoToken Generator

---

🎥 **Generate YouTube PoTokens with ease!**  

This project automates the generation of `{ visitorData, poToken }` pairs, used for YouTube’s PoToken authentication process.

🚀 **Fully automated with GitHub Actions!**  

Credit to [YunzheZJU](https://github.com/YunzheZJU/youtube-po-token-generator)

---


## 📢 Join Our Telegram Channel

🚀 **Want the latest YouTube VisitorData & PoToken automatically?**

Join our Telegram channel "**YouTube VisitorData & PoToken Generator**"

🔹 **AUTOMATICALLY GENERATE 30 YouTube VisitorData & PoToken EVERY 15 MINUTES**

[![Telegram Channel](https://img.shields.io/badge/Telegram_channel-2CA5E0?style=for-the-badge&logo=Telegram&logoColor=white)](https://t.me/potoken_generator)

---

## 📝 Introduction

This project automates the generation of YouTube `visitorData` and `poToken` pairs using the `youtube-po-token-generator` package. The process is handled by a GitHub Actions workflow, which can be **manually triggered** or **scheduled to run automatically**.

---

## ⚙️ How It Works

The workflow performs the following steps:

1. **Checkout Repository** → Ensures the latest code is used.
2. **Install Dependencies** → Installs `youtube-po-token-generator`, `date-fns`, and `axios`.
3. **Generate Data** → Fetches fresh `visitorData` and `poToken` pairs.
4. **Log & Upload** → Saves results in `generated_results.log` and uploads them as an artifact.

---

## 🤖 Automation with GitHub Actions

This project includes a **GitHub Actions workflow** that supports both **manual** and **scheduled execution**.

### 🔹 Manual Trigger
- You can manually start the workflow and specify how many visitor data entries to generate.
- This is useful when you need on-demand PoTokens.

### 🔹 Scheduled Trigger
- The workflow runs **automatically every 15 minutes**.
- Ensures fresh `visitorData` and `poToken` pairs are generated consistently.

---

## 📁 Output & Logs

All generated tokens are **logged in `generated_results.log`** and uploaded as an artifact in GitHub.

The file contains entries like:

```
------------------------------------------
🎥 YOUTUBE VISITORDATA & POTOKEN GENERATOR
------------------------------------------

👤 CREATED BY Okki Dwi
🔄 FORKED FROM [YunzheZJU](https://github.com/YunzheZJU/youtube-po-token-generator)

🌐 VISIT: [GitHub Repo](https://github.com/okkidwi/youtube-visitordata-potoken-generator)

------------------------------------------

ENTRY #1

------------------------------------------

📆 Timestamp: 2025-02-07 12:00:00 UTC

🔹 VisitorData: VISITOR123XYZ

🔑 PoToken: TOKEN-ABCDEFG

------------------------------------------
```

---

## 🛠️ Related Works

This project is inspired by:
📌 [iv-org/youtube-trusted-session-generator](https://github.com/iv-org/youtube-trusted-session-generator)

---

## 🔄 Forked From

This repository was **forked from**:
📌 [YunzheZJU/youtube-po-token-generator](https://github.com/YunzheZJU/youtube-po-token-generator)

---

## 📌 Additional Notes

- **Debugging YouTube’s PoToken system** is complex due to constant changes.
- **Altering injected scripts or userAgent settings** may affect PoToken validity.

---

🚀 **Enjoy the automation!** If you find this useful, feel free to fork & contribute! 😊
