<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "d20dfd93913355addc3b496d889b1618",
  "translation_date": "2026-01-12T14:48:36+00:00",
  "source_file": "README.md",
  "language_code": "fa"
}
-->
![Header Banner](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# سلام، من مین‌سئوک سانگ هستم!

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**خالق [Localizeflow](https://localizeflow.com)**

**دارنده جایزه Microsoft AI MVP • نگهدارنده OSS پروژه [Azure/co-op-translator](https://github.com/Azure/co-op-translator)**

من عاشق ساخت ابزارهای توسعه‌دهنده متن‌باز مجهز به هوش مصنوعی هستم که به صورت جهانی مقیاس‌پذیر بوده و مفاهیم اولیه را به راه‌حل‌های آماده تولید با تأثیر واقعی تبدیل می‌کنند.

### 🌐 پشتیبانی چندزبانه

#### پشتیبانی شده توسط [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](./README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **ترجیح می‌دهید به صورت محلی کلون کنید؟**

> این مخزن شامل بیش از ۵۰ ترجمه زبان است که حجم دانلود را به طور قابل توجهی افزایش می‌دهد. برای کلون بدون ترجمه‌ها، از sparse checkout استفاده کنید:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> این به شما همه چیز لازم برای کامل کردن دوره را با دانلود بسیار سریع‌تر می‌دهد.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## پروژه‌های کلیدی

### 🚀 Localizeflow (پروژه فعلی)
**گردش کار ترجمه خودکار مستندات به‌صورت پیش‌فرض GitHub**  
بدون نیاز به تنظیم. میزبانی شده. همگام‌سازی خودکار برای پروژه‌های چندزبانه.  
→ https://localizeflow.com

- به‌طور خودکار تغییرات در فایل‌های منبع شما را شناسایی می‌کند
- تنها موارد تغییر یافته را ترجمه می‌کند
- برای هر زبان PR باز می‌کند
- ساخته شده بر پایه Co-op Translator (OSS مایکروسافت آزور)


### **Co-op Translator (مایکروسافت آزور OSS)**

ابزار خط فرمان رسمی OSS آزور که **ترجمه‌های چندزبانه** را برای محتوای Markdown و تصویر (OCR) خودکار می‌کند  
**تأثیر:** قدرت‌بخش ترجمه‌های مخازن آموزشی مایکروسافت با بیش از ۲۰۰ هزار ستاره در مجموع، تضمین محتوای همیشه به‌روز در بیش از ۱۰ زبان.

- از مرحله ابتدایی PoC تا ابزار خط فرمان آماده تولید با پایتون گسترش یافته است
- ادغام Azure OpenAI + Azure AI Vision برای ترجمه و اتوماسیون OCR
- استفاده شده توسط مخازنی مانند:
  - [Generative AI for Beginners](https://github.com/microsoft/Generative-AI-for-beginners) (۸۴ هزار ستاره)
  - [ML for Beginners](https://github.com/microsoft/ML-for-Beginners) (۷۲ هزار ستاره)
  - [AI for Beginners](https://github.com/microsoft/AI-for-Beginners) (۳۷ هزار ستاره)
  - [AI Agents for Beginners](https://github.com/microsoft/AI-Agents-for-Beginners) (۱۷ هزار ستاره)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (۳ هزار ستاره)
- معرفی شده در نمایشگاه OSS **Open at Microsoft**
- دریافت جایزه **Microsoft AI MVP 2025**

---

## سخنرانی‌ها و رسانه‌ها

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – باز کردن دسترسی چندزبانه با Co-op Translator](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – برنامه‌ریزی و آماده‌سازی برای توسعه راه‌حل‌های هوش مصنوعی در آزور](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## تکنولوژی‌های استفاده شده
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

## آمار و فعالیت
<details>
<summary>مشاهده آمار GitHub</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 ارتباط با من
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![Email](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)