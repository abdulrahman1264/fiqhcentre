# 🕌 FiqhCentre — Islamic Knowledge Platform

> **مَرْكَزُ الفِقْهِ الإِسْلَامِي**  
> Knowledge · Understanding · Guidance

A complete Islamic knowledge website powered by AI, live Quran & Hadith APIs, and a library of 36 classical Islamic texts. Built strictly according to **Ahlu Sunnah wal Jama'ah**, covering both **Hanafi** and **Shafi** madhabs.

🌐 **Live Site:** [abdulrahman1264.github.io/fiqhcentre](https://abdulrahman1264.github.io/fiqhcentre)

---

## ✨ Features

### 💬 Knowis AI — Islamic Knowledge Assistant
- Powered by **Claude claude-sonnet-4-20250514** (Anthropic)
- Answers in **English**, **Arabic (عربي)**, and **Tamil (தமிழ்)**
- Strict **Ahlu Sunnah wal Jama'ah** methodology
- Covers both **Hanafi (Al-Hidayah)** and **Shafi (Al-Mahalli)** positions
- Always cites exact **Hadith numbers** and **Surah:Ayat** references
- Web search enabled for live verification of sources

### 📖 Quran Explorer — Live API
- Full **114 Surahs** from live API (`api.alquran.cloud`)
- **Arabic** (Uthmani script) + **English** (Pickthall) + **Tamil** — all three side by side
- Topic-based search with AI-verified Ayat results

### 📜 Hadith Explorer — Live API
- All **9 authentic hadith books** from live database (`fawazahmed0/hadith-api`)
  - Sahih al-Bukhari · Sahih Muslim · Sunan Abu Dawud
  - Jami at-Tirmidhi · Sunan al-Nasa'i · Sunan Ibn Majah
  - Musnad Ahmad · Muwatta Malik · Sunan al-Darimi
- Real **Arabic text** + **English translation** for every hadith
- **Tamil translation** added by Knowis AI
- Topic search with exact hadith number verification

### ⚖️ Fiqh Explorer
- Search any Islamic ruling by topic
- Side-by-side **Hanafi** (Al-Hidayah) and **Shafi** (Al-Mahalli) rulings
- Supporting **Quranic evidence** and **Hadith dalil** in Arabic + English + Tamil
- Exact Kitab references for every ruling

### 📿 Dhikr & Dua
- Authenticated duas with full **Arabic text**
- **English** and **Tamil** translations
- Exact **Hadith reference numbers** for every dua
- Categories: Morning · Evening · After Salah · Before Sleep · Protection · Forgiveness · Travelling · Eating · Tasbih · Entering Masjid

### 📚 Islamic Library — 36 Books
All books hosted on Google Drive, readable in-browser. No download required.

| Category | Books |
|----------|-------|
| **Quran** | Tamil Quran Al-Kareem · The Holy Quran (English) |
| **Tafsir** | Tafsir Al-Jalalayn (Arabic) · Tafsir Al-Jalalayn (English) · Tafsir Ibn Kathir |
| **Hadith** | Sahih al-Bukhari · Sahih Muslim · Jami at-Tirmidhi (6 vols) · Sunan Abu Dawud (5 vols) · Sunan al-Nasai · Sunan Ibn Majah (5 vols) |
| **Fiqh** | Al-Hidayah — Imam al-Marghinani (8 vols) |
| **Usul** | Al-Risalah — Imam al-Shafi'i · Usul al-Hadith · Usul al-Fiqh |

### 🔬 Usul al-Fiqh & Usul al-Hadith
- Visual flowcharts explaining how Islamic rulings are derived
- How Hadith authenticity is graded (Sahih → Da'if → Mawdu')
- The four sources: Quran · Sunnah · Ijma' · Qiyas

### 🌍 Multilingual
- Full **English / Arabic / Tamil** interface
- Language switcher in navbar
- All content responds in the user's chosen language

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Pure HTML5 · CSS3 · Vanilla JavaScript |
| AI Engine | Anthropic Claude claude-sonnet-4-20250514 API |
| Quran Data | [api.alquran.cloud](https://api.alquran.cloud) |
| Hadith Data | [fawazahmed0/hadith-api](https://github.com/fawazahmed0/hadith-api) (CDN) |
| Book Library | Google Drive (iframe embed) |
| Hosting | GitHub Pages |
| Fonts | Playfair Display · Scheherazade New · Outfit (Google Fonts) |

---

## 📂 Repository Structure

```
fiqhcentre/
│
├── fiqhcentre.html        # Main website (single-file application)
└── README.md              # This file
```

> The entire website is a **single HTML file** — no build tools, no dependencies, no npm. Just open in a browser.

---

## 🚀 Deployment

This site is deployed via **GitHub Pages**.

To update the live site:
1. Edit `fiqhcentre.html`
2. Commit and push to the `main` branch
3. GitHub Pages auto-deploys within 1–2 minutes

---

## 📡 APIs Used

### Quran API — alquran.cloud
```
GET https://api.alquran.cloud/v1/surah/{number}/quran-uthmani   # Arabic
GET https://api.alquran.cloud/v1/surah/{number}/en.pickthall    # English
GET https://api.alquran.cloud/v1/surah/{number}/ta.tamil        # Tamil
```
Free · No API key required · Full Quran database

### Hadith API — fawazahmed0/hadith-api
```
GET https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/eng-{book}.min.json
GET https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-{book}.min.json
```
Free · No API key required · All 9 books · Arabic + English

### Anthropic Claude API
```
POST https://api.anthropic.com/v1/messages
Model: claude-sonnet-4-20250514
Features: Web search tool enabled
```
Used for: Knowis AI chat · Fiqh rulings · Dhikr & Dua · Tamil translations · Topic search

---

## 🕌 Islamic Methodology

This platform follows strict **Ahlu Sunnah wal Jama'ah** principles:

- **Hadith sources** — Only the nine authentic books (جامع الكتب التسعة)
- **Fiqh** — Hanafi madhab (Al-Hidayah) and Shafi madhab (Al-Mahalli)
- **Quran** — Uthmani script, Pickthall and classical translations only
- **Tafsir** — Al-Jalalayn and Ibn Kathir (Ahlu Sunnah approved)
- **Aqeedah** — Ahlu Sunnah wal Jama'ah only, deviant sects never cited
- **Fatwa disclaimer** — All Fiqh answers end with: *"For an official Fatwa, consult a qualified Islamic scholar"*

---

## 👥 Contact & Community

| Platform | Handle |
|----------|--------|
| Instagram · Knowis | [@knowis_247](https://www.instagram.com/knowis_247) |
| Instagram · Islamic Homies | [@islamic_homies](https://www.instagram.com/islamic_homies) |

---

## 🤲 Acknowledgements

- **Imam al-Marghinani (RA)** — Al-Hidayah (Hanafi Fiqh)
- **Imam Jalal al-Din al-Mahalli (RA)** — Al-Mahalli (Shafi Fiqh)
- **Imam Jalal al-Din al-Suyuti (RA)** — Tafsir Al-Jalalayn
- **Imam Ibn Kathir (RA)** — Tafsir Ibn Kathir
- **Imam al-Shafi'i (RA)** — Al-Risalah (Usul al-Fiqh)
- **fawazahmed0** — Free Hadith API
- **Islamic Network** — alquran.cloud API
- **Anthropic** — Claude AI

---

## ⚠️ Disclaimer

This platform is for **Islamic education only**. For official religious rulings (Fatwa), always consult a qualified Islamic scholar. The AI responses are generated for educational purposes and should not be taken as formal religious verdicts.

---

<div align="center">

**رَبِّ زِدْنِي عِلْماً**  
*"My Lord, increase me in knowledge"* — Ta-Ha 20:114

© 2025 FiqhCentre · Ahlu Sunnah wal Jama'ah

</div>
