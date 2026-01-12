<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "15f14ebaa9879ea2be727ca61fd489c8",
  "translation_date": "2026-01-12T12:17:21+00:00",
  "source_file": "README.md",
  "language_code": "hi"
}
-->
![Header Banner](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# नमस्ते, मैं मिनसोक सॉन्ग हूँ!

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**[Localizeflow](https://localizeflow.com) के निर्माता**

**Microsoft AI MVP • [Azure/co-op-translator](https://github.com/Azure/co-op-translator) के OSS रखरखावकर्ता**

मैं वैश्विक पैमाने पर काम करने वाले AI-संचालित, ओपन-सोर्स डेवलपर टूल्स बनाना पसंद करता हूँ जो शुरुआती अवधारणाओं को वास्तविक प्रभाव के साथ उत्पादन-तैयार समाधान में बदल देते हैं।

### 🌐 बहुभाषी समर्थन

#### [Localizeflow](https://localizeflow.com/) द्वारा समर्थित

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](./README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **स्थानीय रूप से क्लोन करना पसंद करते हैं?**

> यह रिपॉजिटरी 50+ भाषाओं के अनुवाद शामिल करता है जो डाउनलोड आकार को काफी बढ़ा देता है। बिना अनुवाद के क्लोन करने के लिए, sparse checkout का उपयोग करें:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> यह आपको तेज डाउनलोड के साथ कोर्स पूरा करने के लिए सब कुछ देता है।
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## प्रमुख प्रोजेक्ट

### 🚀 Localizeflow (वर्तमान प्रोजेक्ट)
**GitHub-नेटिव स्वचालित दस्तावेज़ अनुवाद वर्कफ़्लो**  
बिना किसी सेटअप के। होस्टेड। बहुभाषी परियोजनाओं के लिए ऑटो-सिंक।  
→ https://localizeflow.com

- स्वचालित रूप से आपके स्रोत फ़ाइलों में बदलाव पहचानता है
- केवल बदले हुए हिस्सों का अनुवाद करता है
- प्रत्येक भाषा के लिए PR खोलता है
- Co-op Translator (Azure OSS) पर आधारित


### **Co-op Translator (Microsoft Azure OSS)**

एक आधिकारिक Azure OSS CLI जो Markdown + छवि सामग्री (OCR) के लिए **बहुभाषी अनुवाद** को स्वचालित करता है  
**प्रभाव:** Microsoft के शैक्षिक रिपॉजिटरीज़ के लिए अनुवाद संचालित करता है जिनके 200k★+ स्टार हैं, जिससे 10+ भाषाओं में हमेशा अपडेटेड सामग्री सुनिश्चित होती है।

- प्रारंभिक PoC से उत्पादन-ग्रेड Python CLI तक का विकास
- अनुवाद और OCR स्वचालन के लिए Azure OpenAI + Azure AI Vision का एकीकरण
- निम्नलिखित रिपॉजिटरीज़ में उपयोग किया गया:
  - [Generative AI for Beginners](https://github.com/microsoft/Generative-AI-for-beginners) (84k★)
  - [ML for Beginners](https://github.com/microsoft/ML-for-Beginners) (72k★)
  - [AI for Beginners](https://github.com/microsoft/AI-for-Beginners) (37k★)
  - [AI Agents for Beginners](https://github.com/microsoft/AI-Agents-for-Beginners) (17k★)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (3k★)
- **Open at Microsoft** OSS प्रदर्शन में शामिल
- Microsoft AI MVP 2025 पुरस्कार प्राप्त

[![Co-op Translator](https://github-readme-stats.vercel.app/api/pin/?username=Azure&repo=co-op-translator&bg_color=ffffff&title_color=0078D4&text_color=333333&border_color=c0d8f0&border_radius=10)](https://github.com/Azure/co-op-translator)

---

## वार्तालाप और मीडिया

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – Co-op Translator के साथ बहुभाषी पहुँच को अनलॉक करना](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – Azure पर AI समाधान विकसित करने की योजना बनाएं और तैयार करें](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## सम्मान
- **Microsoft Most Valuable Professional (AI)** 2024–2025
- **1st Place**, Inha University Open Source Festival (Co-op Translator)
- **विजेता**, Microsoft Korea Azurethon (प्रॉम्प्ट इंजीनियरिंग श्रेणी)
- **3× सबसे अधिक देखे गए ब्लॉगर**, Microsoft Educator Developer Blog

---

## टेक स्टैक
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

## सांख्यिकी और गतिविधि
<details>
<summary>GitHub सांख्यिकी देखें</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 मुझसे संपर्क करें
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![Email](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)