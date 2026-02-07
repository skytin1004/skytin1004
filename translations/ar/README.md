<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "d20dfd93913355addc3b496d889b1618",
  "translation_date": "2026-01-12T14:47:19+00:00",
  "source_file": "README.md",
  "language_code": "ar"
}
-->
![شريط الرأس](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# مرحبًا، أنا مينسوك سونج!

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**مُبدع [Localizeflow](https://localizeflow.com)**

**خبير مايكروسوفت AI MVP • صاحب وصيانة OSS لـ [Azure/co-op-translator](https://github.com/Azure/co-op-translator)**

أحب بناء أدوات تطوير مفتوحة المصدر مدعومة بالذكاء الاصطناعي وقابلة للتوسع عالمياً لتحويل المفاهيم في مراحلها المبكرة إلى حلول جاهزة للإنتاج لها تأثير حقيقي.

### 🌐 دعم متعدد اللغات

#### مدعوم بواسطة [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](./README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **تفضل الاستنساخ محليًا؟**

> يحتوي هذا المستودع على ترجمات لأكثر من 50 لغة مما يزيد من حجم التنزيل بشكل كبير. للاستنساخ بدون الترجمات، استخدم sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> هذا يمنحك كل ما تحتاجه لإكمال الدورة بتنزيل أسرع بكثير.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## المشروع الرئيسي

### 🚀 Localizeflow (المشروع الحالي)
**سير عمل الترجمة التلقائية للمستندات الأصلي على GitHub**  
بدون إعداد. مستضاف. مزامنة تلقائية للمشاريع متعددة اللغات.  
→ https://localizeflow.com

- يكتشف التغييرات في ملفات المصدر تلقائيًا
- يترجم فقط ما تغير
- يفتح طلبات سحب (PR) لكل لغة
- مبني على Co-op Translator (Azure OSS)


### **Co-op Translator (Microsoft Azure OSS)**

واجهة CLI رسمية لـ Azure OSS تقوم بأتمتة **الترجمات متعددة اللغات** لمحتوى Markdown + الصور (OCR)  
**التأثير:** يدعم الترجمات في مستودعات Microsoft التعليمية التي تتجاوز 200 ألف نجمة★، لضمان محتوى مُحدث دائمًا بأكثر من 10 لغات.

- تطور من إثبات مفهوم مبكر → أداة CLI بإنتاجية عالية مكتوبة بلغة Python
- دمج Azure OpenAI + Azure AI Vision للترجمة + أتمتة OCR
- مستخدم في مستودعات مثل:
  - [الذكاء الاصطناعي التوليدي للمبتدئين](https://github.com/microsoft/Generative-AI-for-beginners) (84k★)
  - [التعلم الآلي للمبتدئين](https://github.com/microsoft/ML-for-Beginners) (72k★)
  - [الذكاء الاصطناعي للمبتدئين](https://github.com/microsoft/AI-for-Beginners) (37k★)
  - [وكلاء الذكاء الاصطناعي للمبتدئين](https://github.com/microsoft/AI-Agents-for-Beginners) (17k★)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (3k★)
- مميز في معرض OSS الخاص بـ **Open at Microsoft**
- حاز على لقب **Microsoft AI MVP لعام 2025**

---

## المحادثات والوسائط

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – فتح إمكانية الوصول متعدد اللغات باستخدام Co-op Translator](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – التخطيط والتحضير لتطوير حلول الذكاء الاصطناعي على Azure](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## تكديس التقنيات
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

## الإحصائيات والنشاط
<details>
<summary>عرض إحصائيات GitHub</summary>

[![الإحصائيات](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![أهم اللغات](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 تواصل معي
[![لينكدإن](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![تويتر](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![الملف الشخصي](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![مجتمع التقنية](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![البريد الإلكتروني](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)