<div align="center">
📖 The Islamic Encyclopedia & Fiqh-e-Muqaran
An Open-Source Movement to Unite the Ummah through Knowledge & Technology
Open Source Love

PRs Welcome

Tech Stack: Node.js | MongoDB | Kotlin
Read this in: 🇸🇦 العربية (Arabic) | 🇵🇰 اردو (Urdu) | 🇮🇳 हिन्दी (Hindi) | 🇮🇩 Bahasa Indonesia | 🇲🇾 Bahasa Melayu (Malay) | 🇹🇷 Türkçe (Turkish) | 🇮🇷 فارسی (Persian) | 🇧🇩 বাংলা (Bengali) | 🇨🇳 中文 (Chinese) | 🇯🇵 日本語 (Japanese) | 🇰🇷 한국어 (Korean) | 🇫🇷 Français (French) | 🇪🇸 Español (Spanish) | 🇩🇪 Deutsch (German) | 🇷🇺 Русский (Russian) | 🇰🇪 Kiswahili (Swahili) | 🇳🇬 Hausa
(Note: Translations for this README in the above languages will be added soon by our community contributors.)
</div>
🌟 The Ultimate Goal & My Dream
> "And hold firmly to the rope of Allah all together and do not become divided." — (Quran 3:103)
> 
The Muslim Ummah today is deeply divided into countless sects (Firkas) and groups. My dream and the core goal of this project is to eliminate these boundaries and bring everyone together simply as "Muslims", just as we were commanded.
We aim to create a platform that provides authentic, evidence-based solutions to everyday Islamic issues (Masail). Instead of dictating rulings based on a specific sect, this project focuses on Fiqh-e-Muqaran (Comparative Jurisprudence). Every single ruling, solution, and piece of advice will be backed directly by clear references from the Holy Quran and authentic Ahadith (Sahih Sunnah).
This is not just an app; it is a movement to unite the Ummah through knowledge, research, and authentic references.
📱 The Complete App Idea & Ecosystem
To achieve this dream, we are building a complete digital ecosystem featuring a robust Web Backend and Cross-Platform Mobile Apps. The platform rests on four main pillars:
 * 📖 The Quranic Center: A highly optimized database containing the Arabic text, Tajweed rules, word-by-word grammar breakdowns, and authentic translations in multiple languages.
 * 📚 The Hadith Library: A fully relational database of the Sihah Sittah (The Authentic Six) and other major Hadith collections, complete with Sanad (chain of narrators) and precise grading (Sahih/Hasan/Zaeef).
 * ⚖️ Ahkam-o-Masail (Daily Solutions): A real-life problem-solving section where everyday issues are addressed. Every ruling contains direct hyperlinks (database IDs) to the exact Quranic Ayah or Hadith that solves it.
 * 🌍 Research Forum (Community Hub): A dedicated, structured platform where researchers, scholars, and ordinary Muslims can discuss rulings, suggest corrections, and provide evidence in an open-source, troll-free environment.
🛠️ Project Development & Hosting Roadmap
This project is massive and requires a modern, highly scalable approach. Here is our tech stack and roadmap:
 * 🗄️ Database Consolidation: We have spent months cleaning, decrypting, and restructuring raw SQLite and JSON data to make it 100% developer-friendly.
 * ⚙️ Backend & Web Development: We are building a blazing-fast backend using Node.js, Express.js, TypeScript, and MongoDB. This REST/GraphQL API will serve as the central brain of the ecosystem.
 * ☁️ Global Hosting: We plan to host this database and API on a highly scalable cloud infrastructure, allowing developers worldwide to access the endpoints for free.
 * 📱 Mobile App: A modern, beautiful, offline-capable Android application built with Kotlin, Jetpack Compose, and Room DB.
📂 What You Will Find in This Repository (Data Assets)
I have spent countless hours extracting, decrypting, and organizing raw Islamic data so you don't have to start from scratch. The data is logically separated into two main directories:
📦 Repository Root
 ┣ 📂 QURAN data
 ┃ ┗ 📜 quran.db              # Fully cleaned, decrypted, and optimized SQLite database of the Quran.
 ┃                            # Includes Arabic text, word-by-word dictionary, topics, and authentic translations.
 ┃
 ┣ 📂 Hadith data
 ┃ ┣ 📂 Books_Json            # The ultimate goldmine for Hadith data (Relational JSONs).
 ┃ ┃ ┣ 📁 Sahih Bukhari       # Perfectly structured with meta.json, chapters.json, subchapters.json,
 ┃ ┃ ┣ 📁 Sahih Muslim        # and separate translation/Arabic/Raavi files.
 ┃ ┃ ┣ 📁 Sunan Abu Dawud     # 100% ready to be imported into MongoDB or any NoSQL/SQL backend.
 ┃ ┃ ┣ 📁 Sunan an-Nasa'i
 ┃ ┃ ┣ 📁 Sunan at-Tirmidhi
 ┃ ┃ ┗ 📁 Sunan Ibn Majah
 ┃ ┃
 ┃ ┗ 📂 DB files              # Additional raw SQLite databases for extended research 
 ┃   ┣ 📜 musnad.db           # (e.g., Musnad Ahmad, Mishkat, Muwatta Imam Malik, etc.).
 ┃   ┣ 📜 mishkat.db
 ┃   ┗ 📜 ... (and more)

🤝 How You Can Contribute & Expand This Project
This project is simply too big for one person. I am making this open-source to invite passionate Muslim developers, data engineers, UI/UX designers, and translators from all over the world to join this Sadaqah Jariyah (continuous charity).
Here is how you can jump in and help:
 * 🌐 Provide Multi-Language Support: Take the existing database structure and add translations of the Quran and Ahadith in your native language (e.g., German, Spanish, Swahili, Malay, Chinese, Japanese).
 * 💻 Backend Development: Help us write robust Node.js/TypeScript scripts to map this JSON/SQLite data into MongoDB and serve it via blazing-fast APIs.
 * 🎨 Frontend & Mobile UI: Contribute to the Android (Jetpack Compose) mobile app or help build an interactive Web (React/Next.js) frontend.
 * 🔍 Data Verification: Help cross-check the Ahadith gradings, translation accuracy, and Fiqh references to ensure 100% authenticity.
Ready to start?
Please read our CONTRIBUTING.md to understand how to fork the repository, set up your local environment, and submit a Pull Request (PR).
<div align="center">
<b>Let's build something that outlasts us. Let's unite the Ummah.</b>

<i>May Allah accept this effort from all of us. Ameen.</i>
</div>
