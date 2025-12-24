<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "b10e09bc8a0f83d3051ae7efdb31c2e5",
  "translation_date": "2025-12-24T05:45:50+00:00",
  "source_file": "README.md",
  "language_code": "ur"
}
-->
![ہیڈر بینر](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# سلام، میں Minseok Song ہوں! 

[![GitHub اسپانسرز](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![ایک کافی خریدیں](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**[Localizeflow](https://localizeflow.com) کے خالق**

**Microsoft AI MVP • [Azure/co-op-translator](https://github.com/Azure/co-op-translator) کا OSS مینٹینر**

میں عالمی سطح پر پھیلنے والے، AI سے لیس اوپن سورس ڈیولپر ٹولز بنانا پسند کرتا ہوں جو ابتدائی مرحلے کے تصورات کو حقیقی اثر کے ساتھ پروڈکشن-قابل حل میں بدل دیتے ہیں۔

### 🌐 متعدد زبانوں کی حمایت

#### [Localizeflow](https://localizeflow.com/) کی معاونت

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[عربی](../ar/README.md) | [بنگالی](../bn/README.md) | [بلغاری](../bg/README.md) | [برمی (میانمار)](../my/README.md) | [چینی (سادہ)](../zh/README.md) | [چینی (روایتی، ہانگ کانگ)](../hk/README.md) | [چینی (روایتی، مکاو)](../mo/README.md) | [چینی (روایتی، تائیوان)](../tw/README.md) | [کروشین](../hr/README.md) | [چیک](../cs/README.md) | [ڈینش](../da/README.md) | [ڈچ](../nl/README.md) | [ایسٹونین](../et/README.md) | [فنلندی](../fi/README.md) | [فرانسیسی](../fr/README.md) | [جرمن](../de/README.md) | [یونانی](../el/README.md) | [عبرانی](../he/README.md) | [ہندی](../hi/README.md) | [ہنگیرین](../hu/README.md) | [انڈونیشیائی](../id/README.md) | [اطالوی](../it/README.md) | [جاپانی](../ja/README.md) | [کنڑا](../kn/README.md) | [کوریائی](../ko/README.md) | [لتھوانیائی](../lt/README.md) | [ملائی](../ms/README.md) | [مالایالم](../ml/README.md) | [مراٹھی](../mr/README.md) | [نیپالی](../ne/README.md) | [نائجیریائی پِڈگن](../pcm/README.md) | [نارویجیائی](../no/README.md) | [فارسی (Farsi)](../fa/README.md) | [پولش](../pl/README.md) | [پرتگالی (برازیل)](../br/README.md) | [پرتگالی (پرتگال)](../pt/README.md) | [پنجابی (گرمکھی)](../pa/README.md) | [رومانیائی](../ro/README.md) | [روسی](../ru/README.md) | [سربیائی (سِرِیلک)](../sr/README.md) | [سلوواک](../sk/README.md) | [سلووینیائی](../sl/README.md) | [ہسپانوی](../es/README.md) | [سواحلی](../sw/README.md) | [سویڈش](../sv/README.md) | [تاگالوگ (فلپائنی)](../tl/README.md) | [تمل](../ta/README.md) | [تیلگو](../te/README.md) | [تھائی](../th/README.md) | [ترکی](../tr/README.md) | [یوکرینی](../uk/README.md) | [اردو](./README.md) | [ویتنامی](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## اہم پروجیکٹ

### 🚀 Localizeflow (موجودہ پروجیکٹ)
**GitHub-نیٹو خودکار دستاویزات کا ترجمہ ورک فلو**  
کوئی سیٹ اپ نہیں۔ ہوسٹڈ۔ متعدد زبانوں والے پروجیکٹس کے لیے آٹو-سنک۔  
→ https://localizeflow.com

- آپ کی سورس فائلز میں تبدیلیوں کا خودکار پتہ لگاتا ہے
- صرف جو تبدیل ہوا اسے ترجمہ کرتا ہے
- ہر زبان کے لیے PR کھولتا ہے
- Co-op Translator (Azure OSS) پر بنایا گیا


### **Co-op Translator (Microsoft Azure OSS)**

ایک سرکاری Azure OSS CLI جو Markdown اور امیج مواد (OCR) کے لیے **کثیراللسانی تراجم** کو خودکار بناتا ہے  
**اثر:** Microsoft کے تعلیمی رپوزٹریز کے لیے تراجم کو چلانا جو مجموعی طور پر 200k★+ ہیں، یہ یقینی بناتے ہوئے کہ مواد 10+ زبانوں میں ہمیشہ اپ ٹو ڈیٹ رہے۔

- ابتدائی PoC سے لے کر پروڈکشن-گریڈ Python CLI تک پیمانہ بڑھایا گیا
- ترجمہ اور OCR آٹومیشن کے لیے Azure OpenAI + Azure AI Vision کو انٹیگریٹ کیا گیا
- درج ذیل رپوزٹریز میں استعمال ہوتا ہے:
  - [Generative AI for Beginners](https://github.com/microsoft/Generative-AI-for-beginners) (84k★)
  - [ML for Beginners](https://github.com/microsoft/ML-for-Beginners) (72k★)
  - [AI for Beginners](https://github.com/microsoft/AI-for-Beginners) (37k★)
  - [AI Agents for Beginners](https://github.com/microsoft/AI-Agents-for-Beginners) (17k★)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (3k★)
- **Open at Microsoft** OSS شوکیس میں نمایاں
- **Microsoft AI MVP 2025** حاصل کیا

[![Co-op Translator](https://github-readme-stats.vercel.app/api/pin/?username=Azure&repo=co-op-translator&bg_color=ffffff&title_color=0078D4&text_color=333333&border_color=c0d8f0&border_radius=10)](https://github.com/Azure/co-op-translator)

---

## تقاریر اور میڈیا

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – Co-op Translator کے ساتھ کثیر اللسانی رسائی کو فعال کرنا](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – Azure پر AI حل تیار کرنے کے لیے منصوبہ بندی اور تیاری](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## تسلیمات
- **Microsoft Most Valuable Professional (AI)** 2024–2025
- **پہلا مقام**, Inha University Open Source Festival (Co-op Translator)
- **فاتح**, Microsoft Korea Azurethon (Prompt Engineering زمرہ)
- **3× سب سے زیادہ دیکھے جانے والے بلاگر**, Microsoft Educator Developer Blog

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

## اعداد و شمار اور سرگرمی
<details>
<summary>GitHub اعداد و شمار دیکھیں</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 مجھ سے رابطہ کریں
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![ای میل](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)