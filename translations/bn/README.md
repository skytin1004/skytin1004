<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "15f14ebaa9879ea2be727ca61fd489c8",
  "translation_date": "2026-01-12T12:17:49+00:00",
  "source_file": "README.md",
  "language_code": "bn"
}
-->
![Header Banner](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# হাই, আমি মিনসিয়ক সঙ!

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**[Localizeflow](https://localizeflow.com) এর নির্মাতা**

**Microsoft AI MVP • [Azure/co-op-translator](https://github.com/Azure/co-op-translator) এর OSS রক্ষক**

আমি এমন AI-চালিত, ওপেন-সোর্স ডেভেলপার টুল বানাতে ভালোবাসি যা বিশ্বব্যাপী স্কেল করে এবং প্রাথমিক পর্যায়ের ধারণাগুলোকে বাস্তব প্রভাব ফেলা প্রোডাকশন-রেডি সমাধানে রূপান্তর করে।

### 🌐 বহু-ভাষা সমর্থন

#### [Localizeflow](https://localizeflow.com/) দ্বারা সমর্থিত

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](./README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **লোকালি ক্লোন করতে চান?**

> এই রিপোজিটরিটি ৫০+ ভাষার অনুবাদ অন্তর্ভুক্ত করে যার ফলে ডাউনলোড সাইজ অনেক বাড়ে। অনুবাদ ছাড়া ক্লোন করতে sparse checkout ব্যবহার করুন:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> যা আপনাকে দ্রুত ডাউনলোডের মাধ্যমে কোর্স সম্পন্ন করার জন্য সবকিছু দেয়।
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## মূল প্রকল্প

### 🚀 Localizeflow (বর্তমান প্রকল্প)
**GitHub-নেটিভ স্বয়ংক্রিয় ডকুমেন্টেশন অনুবাদ ওয়ার্কফ্লো**  
জিরো সেটআপ। হোস্টেড। বহু-ভাষার প্রকল্পের জন্য অটো-সিঙ্ক।  
→ https://localizeflow.com

- স্বয়ংক্রিয়ভাবে আপনার সোর্স ফাইলের পরিবর্তন শনাক্ত করে
- শুধু পরিবর্তিত অংশ অনুবাদ করে
- প্রত্যেক ভাষার জন্য PR খোলা হয়
- Co-op Translator (Azure OSS) এর উপর নির্মিত


### **Co-op Translator (Microsoft Azure OSS)**

একটি অফিসিয়াল Azure OSS CLI যা Markdown + চিত্র সামগ্রীর (OCR) **বহু-ভাষার অনুবাদ** স্বয়ংক্রিয় করে  
**প্রভাব:** Microsoft এর শিক্ষামূলক রিপোজিটরিগুলোর মোট ২০০ক★+ অনুবাদের শক্তি প্রদান করে, যা ১০+ ভাষায় সর্বদা হালনাগাদ কন্টেন্ট নিশ্চিত করে।

- প্রাথমিক PoC থেকে উৎপাদন-গ্রেড পাইথন CLI তে প্রবেশ করেছে
- অনুবাদ + OCR স্বয়ংক্রিয়তার জন্য Azure OpenAI + Azure AI Vision একীভূত করেছে
- নিম্নলিখিত রিপোজগুলো ব্যবহার করে:
  - [Generative AI for Beginners](https://github.com/microsoft/Generative-AI-for-beginners) (৮৪ক★)
  - [ML for Beginners](https://github.com/microsoft/ML-for-Beginners) (৭২ক★)
  - [AI for Beginners](https://github.com/microsoft/AI-for-Beginners) (৩৭ক★)
  - [AI Agents for Beginners](https://github.com/microsoft/AI-Agents-for-Beginners) (১৭ক★)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (৩ক★)
- **Open at Microsoft** OSS প্রদর্শনীতে অন্তর্ভুক্ত
- পেয়েছেন **Microsoft AI MVP ২০২৫**

[![Co-op Translator](https://github-readme-stats.vercel.app/api/pin/?username=Azure&repo=co-op-translator&bg_color=ffffff&title_color=0078D4&text_color=333333&border_color=c0d8f0&border_radius=10)](https://github.com/Azure/co-op-translator)

---

## বক্তৃতা ও মিডিয়া

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – Co-op Translator দিয়ে বহু-ভাষার প্রবেশযোগ্যতা উন্মোচন](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – Azure-তে AI সমাধান বিকাশের জন্য পরিকল্পনা এবং প্রস্তুতি](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## স্বীকৃতি
- **মাইক্রোসফট মোস্ট ভ্যালুয়েবল প্রফেশনাল (AI)** ২০২৪–২০২৫
- **১ম স্থান**, ইনহা বিশ্ববিদ্যালয় ওপেন সোর্স উৎসব (Co-op Translator)
- **জয়ী**, Microsoft Korea Azurethon (Prompt Engineering বিভাগ)
- **৩× সর্বাধিক দেখা ব্লগার**, Microsoft Educator Developer Blog

---

## প্রযুক্তি স্ট্যাক
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

## স্ট্যাটস ও কার্যক্রম
<details>
<summary>GitHub স্ট্যাটস দেখুন</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 আমার সঙ্গে যোগাযোগ করুন
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![Email](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)