<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "15f14ebaa9879ea2be727ca61fd489c8",
  "translation_date": "2026-01-12T12:24:29+00:00",
  "source_file": "README.md",
  "language_code": "th"
}
-->
![Header Banner](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# สวัสดีครับ ผมมินซอก ซอง!

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**ผู้สร้าง [Localizeflow](https://localizeflow.com)**

**Microsoft AI MVP • ผู้ดูแล OSS ของ [Azure/co-op-translator](https://github.com/Azure/co-op-translator)**

ผมชอบสร้างเครื่องมือสำหรับนักพัฒนาที่ขับเคลื่อนด้วย AI แบบโอเพ่นซอร์ส ที่สามารถขยายขนาดไปทั่วโลก แปลงแนวคิดในระยะเริ่มต้นให้เป็นโซลูชันที่พร้อมสำหรับการใช้งานจริงและมีผลกระทบจริง

### 🌐 รองรับหลายภาษา

#### สนับสนุนโดย [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](./README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **ต้องการโคลนในเครื่องใช่ไหม?**

> ที่เก็บนี้รวมการแปลกว่า 50 ภาษา ซึ่งทำให้ขนาดดาวน์โหลดเพิ่มขึ้นอย่างมาก หากต้องการโคลนโดยไม่รวมการแปล ให้ใช้ sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> สิ่งนี้จะให้ทุกอย่างที่คุณต้องการเพื่อทำหลักสูตรให้เสร็จด้วยความเร็วในการดาวน์โหลดที่เร็วขึ้นมาก
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## โครงการสำคัญ

### 🚀 Localizeflow (โครงการปัจจุบัน)
**เวิร์กโฟลว์การแปลเอกสารอัตโนมัติที่เนทีฟกับ GitHub**  
ไม่ต้องตั้งค่า โฮสต์อยู่แล้ว ซิงค์อัตโนมัติสำหรับโครงการหลายภาษา  
→ https://localizeflow.com

- ตรวจจับการเปลี่ยนแปลงในไฟล์ต้นทางของคุณโดยอัตโนมัติ
- แปลเฉพาะสิ่งที่มีการเปลี่ยนแปลง
- เปิด pull request สำหรับแต่ละภาษา
- สร้างบนฐานของ Co-op Translator (Azure OSS)

### **Co-op Translator (Microsoft Azure OSS)**

CLI OSS อย่างเป็นทางการของ Azure ที่ทำการแปล **หลายภาษาอัตโนมัติ** สำหรับ Markdown + เนื้อหาภาพ (OCR)  
**ผลกระทบ:** สนับสนุนการแปลสำหรับที่เก็บข้อมูลการศึกษาของ Microsoft ที่มีดาวรวมกว่า 200k★+ รับประกันเนื้อหาเป็นปัจจุบันในกว่า 10 ภาษา

- ขยายจาก PoC ระยะแรกเป็น CLI Python ที่ระดับโปรดักชัน
- ผสาน Azure OpenAI + Azure AI Vision สำหรับแปลและ OCR อัตโนมัติ
- ใช้งานโดยที่เก็บเช่น:
  - [Generative AI for Beginners](https://github.com/microsoft/Generative-AI-for-beginners) (84k★)
  - [ML for Beginners](https://github.com/microsoft/ML-for-Beginners) (72k★)
  - [AI for Beginners](https://github.com/microsoft/AI-for-Beginners) (37k★)
  - [AI Agents for Beginners](https://github.com/microsoft/AI-Agents-for-Beginners) (17k★)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (3k★)
- ได้รับการนำเสนอในงานแสดง OSS ของ **Open at Microsoft**
- ได้รับรางวัล **Microsoft AI MVP 2025**

[![Co-op Translator](https://github-readme-stats.vercel.app/api/pin/?username=Azure&repo=co-op-translator&bg_color=ffffff&title_color=0078D4&text_color=333333&border_color=c0d8f0&border_radius=10)](https://github.com/Azure/co-op-translator)

---

## บรรยายและสื่อ

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – ปลดล็อกการเข้าถึงหลายภาษาด้วย Co-op Translator](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – วางแผนและเตรียมพัฒนาโซลูชัน AI บน Azure](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## รางวัลและเกียรติยศ
- **Microsoft Most Valuable Professional (AI)** 2024–2025
- **รางวัลที่ 1** เทศกาลโอเพ่นซอร์ส มหาวิทยาลัย Inha (Co-op Translator)
- **ผู้ชนะ** Microsoft Korea Azurethon (หมวด Prompt Engineering)
- **3× บล็อกเกอร์ที่มีผู้ชมมากที่สุด** บล็อกนักพัฒนาการศึกษา Microsoft

---

## เทคโนโลยีที่ใช้
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

## สถิติและกิจกรรม
<details>
<summary>ดูสถิติ GitHub</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 ติดต่อกับผม
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![Email](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)