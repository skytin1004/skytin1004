<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "d20dfd93913355addc3b496d889b1618",
  "translation_date": "2026-01-12T14:49:13+00:00",
  "source_file": "README.md",
  "language_code": "ur"
}
-->
![ہیڈر بینر](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# ہیلو، میں منسئوک سانگ ہوں!

[![GitHub اسپانسرز](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![مجھے کافی خریدیں](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**[Localizeflow](https://localizeflow.com) کے خالق**

**Microsoft AI MVP • [Azure/co-op-translator](https://github.com/Azure/co-op-translator) کے OSS مینٹینر**

میں AI پر مبنی، اوپن سورس ڈیولپر ٹولز بنانا پسند کرتا ہوں جو عالمی سطح پر پھیلتے ہیں، ابتدائی تصورات کو حقیقی اثر کے ساتھ پروڈکشن-ریڈی حل میں تبدیل کرتے ہیں۔

### 🌐 کثیراللسانی سپورٹ

#### [Localizeflow](https://localizeflow.com/) کی طرف سے سپورٹ شدہ

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](./README.md) | [Vietnamese](../vi/README.md)

> **کیا آپ مقامی طور پر کلون کرنا پسند کریں گے؟**

> یہ ریپوزٹری 50+ زبانوں کے تراجم پر مشتمل ہے جو ڈاؤن لوڈ سائز کو نمایاں طور پر بڑھاتے ہیں۔ تراجم کے بغیر کلون کرنے کے لیے sparse checkout استعمال کریں:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> یہ آپ کو وہ سب کچھ دیتا ہے جو آپ کورس مکمل کرنے کے لیے چاہتے ہیں، بہت تیز ڈاؤن لوڈ کے ساتھ۔
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## کلیدی پروجیکٹ

### 🚀 Localizeflow (موجودہ پروجیکٹ)
**GitHub-نیٹو خودکار دستاویزات ترجمہ ورک فلو**  
زرو سیٹ اپ۔ ہوسٹڈ۔ کثیراللسانی پروجیکٹس کے لیے خودکار ہم آہنگی۔  
→ https://localizeflow.com

- آپ کے سورس فائلوں میں تبدیلیاں خود بخود شناخت کرتا ہے
- صرف جو بدلا ہے اس کا ترجمہ کرتا ہے
- ہر زبان کے لیے PR کھولتا ہے
- Co-op Translator (Azure OSS) پر مبنی


### **Co-op Translator (Microsoft Azure OSS)**

ایک سرکاری Azure OSS CLI جو Markdown + تصویر کے مواد (OCR) کے لیے **کثیراللسانی تراجم** کو خودکار بناتا ہے  
**اثرات:** Microsoft کے تعلیمی ریپوزٹریز کے لیے 200k★+ کے مجموعی تراجم کی طاقت دیتا ہے، ہمیشہ 10+ زبانوں میں اپ ٹو ڈیٹ مواد کو یقینی بناتا ہے۔

- ابتدائی PoC سے لے کر پروڈکشن گریڈ Python CLI تک بڑھا
- Azure OpenAI + Azure AI Vision کو ترجمہ + OCR آٹومیشن کے لیے ضم کیا
- ان ریپوز جیسی جگہوں پر استعمال ہوتا ہے:
  - [Generative AI for Beginners](https://github.com/microsoft/Generative-AI-for-beginners) (84k★)
  - [ML for Beginners](https://github.com/microsoft/ML-for-Beginners) (72k★)
  - [AI for Beginners](https://github.com/microsoft/AI-for-Beginners) (37k★)
  - [AI Agents for Beginners](https://github.com/microsoft/AI-Agents-for-Beginners) (17k★)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (3k★)
- **Open at Microsoft** OSS نمائش میں نمایاں
- **Microsoft AI MVP 2025** حاصل کیا

---

## مذاکرات اور میڈیا

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – Co-op Translator کے ساتھ کثیراللسانی رسائی کو کھولنا](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – Azure پر AI حل تیار کرنے کی منصوبہ بندی اور تیاری](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## ٹیک اسٹیک
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?logo=microsoftazure&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

---

## اعدادوشمار اور سرگرمی
<details>
<summary>GitHub کے اعدادوشمار دیکھیں</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 میرے ساتھ رابطہ کریں
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![Email](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)