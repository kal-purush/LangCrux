<p align="center">
  <img src="logo.png" alt="LangCrux Logo" width="120" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/contributors/kal-purush/LangCrux?color=green&label=contributors" />
  <img src="https://img.shields.io/github/forks/kal-purush/LangCrux?label=forks" />
  <img src="https://img.shields.io/github/stars/kal-purush/LangCrux?label=stars" />
  <img src="https://img.shields.io/github/issues/kal-purush/LangCrux?label=issues" />
  <img src="https://img.shields.io/github/license/kal-purush/LangCrux?label=license" />
</p>

<h1 align="center">LangCrux</h1>

<p align="center">
  A multilingual web dataset focused on language and accessibility.
</p>

<p align="center">
  <a href="https://anonymous.4open.science/w/LangCrux-F68F/">🌐 View Website</a> • 
  <a href="https://anonymous.4open.science/r/LangCrux-F68F/">📦 Get Dataset</a> • 
  <a href="#-how-to-contribute">🤝 Contribute</a>
</p>

---

## 🔍 What is LangCrux?

LangCrux is a dataset of 120,000 websites across 12 countries that use non-Latin scripts. It shows how language appears on the web — both what users read and what screen readers process.

It helps answer:
- What languages are used in visible web content?
- Are accessibility labels written in the same language as the page?
- How often do sites mix native language content with English?

Most existing datasets tell you how popular a site is. LangCrux tells you what language it speaks.

---

## 🌍 What’s in the Dataset?

| Field            | Description                          |
|------------------|--------------------------------------|
| Websites         | 120,000 total                        |
| Countries        | 12                                   |
| Scripts          | Non-Latin (e.g. Arabic, Devanagari)  |
| Source           | Chrome UX Report (CrUX)              |
| Language filter  | Sites with 50%+ content in target language |

| Country      | Language  | Speakers (M) | Sites |
|--------------|-----------|--------------|-------|
| 🇨🇳 China        | Mandarin  | 1200         | 10,000 |
| 🇮🇳 India        | Hindi     | 609          | 10,000 |
| 🇩🇿 Algeria      | Arabic    | 335          | 10,000 |
| 🇧🇩 Bangladesh   | Bangla    | 284          | 10,000 |
| 🇷🇺 Russia       | Russian   | 253          | 10,000 |
| 🇯🇵 Japan        | Japanese  | 126          | 10,000 |
| 🇪🇬 Egypt        | Arabic    | 119          | 10,000 |
| 🇭🇰 Hong Kong    | Cantonese | 85.5         | 10,000 |
| 🇰🇷 South Korea  | Korean    | 82           | 10,000 |
| 🇹🇭 Thailand     | Thai      | 71           | 10,000 |
| 🇬🇷 Greece       | Greek     | 13.5         | 10,000 |
| 🇮🇱 Israel       | Hebrew    | 9            | 10,000 |

---

## 📊 Explore the Data

👉 **Interactive viewer:**  
[https://anonymous.4open.science/w/LangCrux-F68F/](https://anonymous.4open.science/w/LangCrux-F68F/)

### Features

- Each dot = one website  
- Click to see URL, metadata, and language stats  
- Compare visible text vs. accessibility tags  

### Filters

- **Country**  
- **Native Language %**: how much of the site is in the native language  
- **Exact Match Only**: keep only sites where visible and accessibility text are in the same language  
- **Data Sampling**: control sample size (e.g., 100% = full dataset)

⚠ Some websites may include adult content or be inaccessible from some regions.

---

## 🧪 Kizuki: Language-Aware Accessibility Testing

LangCrux includes **Kizuki**, a Lighthouse extension that adds checks for language consistency in:

- `alt`
- `aria-label`
- form `label`s

It helps find mismatches between what’s shown and what assistive tools describe.

---

## 🤝 How to Contribute

Want to help?

You can:
- Suggest new language-country pairs
- Improve language detection logic
- Report bugs in the viewer or audit scripts
- Help with documentation

Open a pull request or issue to get started.

---

## 📄 License

Apache 2.0

---

## 📬 Contact

For questions or feedback, email:  
**langcrux@protonmail.com**
