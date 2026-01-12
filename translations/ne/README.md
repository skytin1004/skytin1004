<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "15f14ebaa9879ea2be727ca61fd489c8",
  "translation_date": "2026-01-12T12:18:57+00:00",
  "source_file": "README.md",
  "language_code": "ne"
}
-->
![Header Banner](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# नमस्ते, म मिन्सेक सङ्ग हुँ! 

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**[Localizeflow](https://localizeflow.com) का सृजक**

**Microsoft AI MVP • [Azure/co-op-translator](https://github.com/Azure/co-op-translator) का OSS मर्मतकर्ता**

म एआई-संचालित, खुला स्रोत विकासकर्ता उपकरणहरू बनाउने मन पराउँछु जसले विश्वव्यापी स्तरमा विस्तार गर्छ र प्रारम्भिक अवधारणाहरूलाई वास्तविक प्रभावसँग उत्पादनमा तयार समाधानहरूमा परिणत गर्छ।

### 🌐 बहुभाषिक समर्थन

#### [Localizeflow](https://localizeflow.com/) द्वारा समर्थित

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](./README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **स्थानीय रूपमा क्लोन गर्न प्राथमिकता दिनुहुन्छ?**

> यस रिपोजिटरीमा ५०+ भाषा अनुवादहरू समावेश छन् जसले डाउनलोड आकार उल्लेखनीय रूपमा बढाउँछ। अनुवादहरू बिना क्लोन गर्न, sparse checkout प्रयोग गर्नुहोस्:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> यसले तपाईंलाई कोर्स पूरा गर्न आवश्यक सबै कुरा धेरै छिटो डाउनलोडको साथ दिन्छ।
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## मुख्य परियोजना

### 🚀 Localizeflow (हालको परियोजना)
**GitHub-नेटिभ स्वचालित डकुमेन्टेसन अनुवाद कार्यप्रवाह**  
शून्य सेटअप। होस्ट गरिएको। बहुभाषिक परियोजनाहरूका लागि अटो-सिंक।  
→ https://localizeflow.com

- स्वतः तपाईंको स्रोत फाइलहरूमा भएका परिवर्तनहरू पत्ता लगाउँछ
- केवल जे परिवर्तन भयो त्यो अनुवाद गर्छ
- हरेक भाषाको लागि PR खोल्छ
- Co-op Translator (Azure OSS) मा बनाइएको


### **Co-op Translator (Microsoft Azure OSS)**

Markdown + छवि सामग्री (OCR) को लागि **बहुभाषिक अनुवादहरू** स्वचालित गर्ने आधिकारिक Azure OSS CLI  
**प्रभाव:** Microsoft शैक्षिक रिपोजिटरीहरूका लागि २००k★+ भन्दा बढी अनुवादहरू प्रोत्साहित गर्दछ, जसले सधैं अपडेट हुने सामग्री १०+ भाषामा सुनिश्चित गर्दछ।

- प्रारम्भिक PoC बाट उत्पादन-ग्रेड पायथन CLI सम्म विस्तार
- अनुवाद + OCR स्वचालनका लागि Azure OpenAI + Azure AI Vision समाकालीन
- यी रिपोजिटरीहरूद्वारा प्रयोग गरिएको:
  - [Generative AI for Beginners](https://github.com/microsoft/Generative-AI-for-beginners) (८४k★)
  - [ML for Beginners](https://github.com/microsoft/ML-for-Beginners) (७२k★)
  - [AI for Beginners](https://github.com/microsoft/AI-for-Beginners) (३७k★)
  - [AI Agents for Beginners](https://github.com/microsoft/AI-Agents-for-Beginners) (१७k★)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (३k★)
- **Open at Microsoft** OSS शोकेसमा समावेश
- **Microsoft AI MVP 2025** पुरस्कार विजेता

[![Co-op Translator](https://github-readme-stats.vercel.app/api/pin/?username=Azure&repo=co-op-translator&bg_color=ffffff&title_color=0078D4&text_color=333333&border_color=c0d8f0&border_radius=10)](https://github.com/Azure/co-op-translator)

---

## वार्ता र मिडिया

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – Co-op Translator सँग बहुभाषिक पहुँच योग्यता अनलक गर्दै](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – Azure मा AI समाधान विकास गर्न योजना बनाउने र तयार गर्ने](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## सम्मान
- **Microsoft Most Valuable Professional (AI)** २०२४–२०२५
- **१ स्थान**, Inha University Open Source Festival (Co-op Translator)
- **विजेता**, Microsoft Korea Azurethon (Prompt Engineering श्रेणी)
- **३× सबैभन्दा बढी हेरिएको ब्लगर**, Microsoft Educator Developer Blog

---

## प्रविधि स्ट्याक
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

## तथ्यांक र क्रियाकलाप
<details>
<summary>GitHub तथ्यांक हेर्नुहोस्</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 मसँग जडान हुनुहोस्
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![Email](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)