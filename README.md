# 🟩 Green Dots Generator (GitHub Activity Template)

This repository is a **learning-focused GitHub Actions template** that demonstrates
how scheduled workflows, automation, and commits work on GitHub.

It can generate **automated contribution activity**
(light, medium, and dark green squares) for educational and experimental purposes.

---

## 🔁 How to Use This Repository

This repository is meant to be **forked or used as a template**.

You should **not run this directly in someone else’s repository**.

### 👉 To get started:
1. Click **Use this template** (recommended)
   **or**
2. Fork this repository to your own GitHub account

Each user must run this in **their own repository** so commits are:
- Attributed correctly
- Shown on their own contribution graph
- Fully under their control

---

## 🎓 Learning & Ethics Disclaimer

> ⚠️ **Important**
>
> This project is intended **solely for learning, experimentation, and personal use**, including:
> - Learning GitHub Actions
> - Understanding automation and CI/CD
> - Testing contribution graph behavior
> - Personal motivation or visual customization
>
> **This repository does NOT represent real development work.**
>
> Do **not** use automated contributions from this project to:
> - Misrepresent professional experience
> - Mislead employers, clients, or collaborators
> - Claim activity as evidence of real-world productivity
>
> Contribution graphs are **not a reliable measure of skill or work**.

---

## ✨ Features

- ✅ Demonstrates scheduled GitHub Actions
- 🎨 Mixed contribution intensity (light / medium / dark)
- ⬜ Some empty days (natural-looking patterns)
- 📆 Optional backfill for past dates
- 👤 Commits show your name & avatar
- 🧩 No local scripts required
- 🔁 Fully forkable / reusable template

---

## 🚀 Quick Start (2 minutes)

### 1️⃣ Use this template
Click **“Use this template”** (or fork the repo).

---

### 2️⃣ Add your GitHub email as a secret

Go to:
**Repo → Settings → Secrets and variables → Actions → New repository secret**

- **Name:** `GITHUB_EMAIL`
- **Value:** `123456+your-username@users.noreply.github.com`
or your verified email

📌 The email must exactly match one listed in  
**GitHub → Settings → Emails**

---

### 3️⃣ Done 🎉
- Daily workflow runs automatically
- Contribution activity may appear within 24 hours

---

## 📆 Backfill Past Activity (Optional)

This feature exists to **demonstrate how commit dates affect contribution graphs**.

1. Go to **Actions**
2. Select **Backfill Green Dots**
3. Click **Run workflow**
4. Enter dates, for example:
start_date: 2025-01-01
end_date: 2025-01-14


⏳ Graph updates usually appear within a few minutes.

---

## 🎨 How the colors work

| Commits/day | Graph color |
|------------|------------|
| 0          | ⬜ none |
| 1–2        | 🟩 light |
| 3–4        | 🟩🟩 medium |
| 5–8        | 🟩🟩🟩 dark |

Weekend activity is intentionally lighter.

---

## 🛠 Learning Ideas

This repo is a great starting point to learn how to:
- Modify cron schedules
- Use secrets in GitHub Actions
- Control commit metadata
- Experiment with CI/CD automation

---

## 📄 License
MIT — free to use, modify, and learn from.

