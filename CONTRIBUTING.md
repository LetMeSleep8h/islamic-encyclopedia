# 🤝 Contributing to The Islamic Encyclopedia & Fiqh-e-Muqaran

**Assalamu Alaikum (Peace be upon you)!** 🌍

Thank you for your interest in contributing to **The Islamic Encyclopedia & Fiqh-e-Muqaran**. This project is more than just code; it is a movement to unite the Muslim Ummah through authentic knowledge, evidence-based research, and technology. By contributing here, you are building a *Sadaqah Jariyah* (continuous charity) that will benefit millions of people, Insha'Allah.

We welcome everyone—from seasoned developers and UI/UX designers to translators, data engineers, and Islamic scholars.

---

## 🕊️ Our Core Philosophy & Code of Conduct
1. **Unite, Don't Divide:** This project strictly focuses on *Fiqh-e-Muqaran* (Comparative Jurisprudence). We do not promote sectarianism (Firqabandi) or bias.
2. **Evidence-Based Only:** Every ruling, solution, or piece of advice added to the platform must be backed by a clear reference from the Holy Quran or Authentic Ahadith (Sahih Sunnah).
3. **Respectful Environment:** We maintain a strictly troll-free, polite, and academic environment in our issues and pull requests.

---

## 🚀 How Can I Contribute?

There is a lot of work to be done. You can jump into any of the following areas:

### 1. 🌐 Translation & Data Expansion
We have massive SQLite and JSON databases of the Quran and Hadith. We need contributors to:
* Translate the Quranic and Hadith databases into regional languages (e.g., German, Spanish, Malay, Swahili, Urdu, Hindi, Chinese).
* Help verify the Arabic text and *Tashkeel* (diacritics).

### 2. ⚙️ Backend & API (Node.js & MongoDB)
* Write robust Node.js/TypeScript scripts to map and import our raw JSON/SQLite data into MongoDB.
* Help design and optimize RESTful or GraphQL API endpoints for the mobile and web apps.

### 3. 📱 Mobile & Web App (Kotlin & Compose)
* Contribute to our Android mobile application using Kotlin and Jetpack Compose.
* Improve UI/UX designs for better readability of Arabic text and translations.

### 4. 🔍 Data Verification & Research
* Islamic researchers can help cross-check Hadith gradings (Sahih/Hasan/Zaeef) and ensure the accuracy of Fiqh references linking to daily problems (Ahkam-o-Masail).

---

## 🛠️ The Development Workflow (How to submit a PR)

To contribute your work, please follow the standard GitHub Flow:

### Step 1: Fork & Clone
1. **Fork** this repository to your own GitHub account.
2. **Clone** it locally to your machine (or Android Termux environment):
   ```bash
   git clone [https://github.com/YOUR_USERNAME/islamic-encyclopedia.git](https://github.com/YOUR_USERNAME/islamic-encyclopedia.git)

Step 2: Create a Branch
Always create a new branch for your feature or bug fix. Do not work directly on the main branch.
git checkout -b feature/swahili-translation
# OR
git checkout -b fix/node-importer-script

Step 3: Make Your Changes & Commit
Make your changes, ensure your code/data is clean, and write a descriptive commit message.
git add .
git commit -m "feat: added Swahili translation for Sahih Bukhari chapter 1"

Step 4: Push & Open a Pull Request (PR)
Push the branch to your forked repository:
git push origin feature/swahili-translation

Go to the original repository on GitHub and click "Compare & pull request". Write a clear description of what you have added or fixed.
⚠️ Important Note Regarding Large Data Files (Git limits)
This repository hosts massive Islamic databases (.db and .json files). Please be aware that GitHub strictly rejects any single file larger than 100 MB.
 * If you are modifying databases, ensure no single file exceeds 90 MB.
 * If a file is larger, it must be compressed (ZIP) or split before pushing.
<div align="center">
<b>Let's build something that outlasts us.</b>

<i>May Allah accept your efforts and time. Ameen.</i>
</div>
