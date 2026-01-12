<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "15f14ebaa9879ea2be727ca61fd489c8",
  "translation_date": "2026-01-12T12:28:47+00:00",
  "source_file": "README.md",
  "language_code": "vi"
}
-->
![Header Banner](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# Chào bạn, mình là Minseok Song!

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**Người tạo ra [Localizeflow](https://localizeflow.com)**

**Microsoft AI MVP • Người duy trì OSS của [Azure/co-op-translator](https://github.com/Azure/co-op-translator)**

Tôi yêu thích xây dựng các công cụ dành cho nhà phát triển mã nguồn mở được hỗ trợ bởi AI có khả năng mở rộng toàn cầu, chuyển đổi các ý tưởng giai đoạn đầu thành các giải pháp sản xuất có tác động thực tế.

### 🌐 Hỗ trợ đa ngôn ngữ

#### Được hỗ trợ bởi [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](./README.md)

> **Muốn sao chép về máy tính?**

> Kho lưu trữ này bao gồm hơn 50 bản dịch ngôn ngữ, làm tăng đáng kể kích thước tải xuống. Để sao chép mà không có bản dịch, hãy dùng sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Điều này cung cấp cho bạn mọi thứ cần thiết để hoàn thành khóa học với tốc độ tải nhanh hơn nhiều.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## Dự Án Chính

### 🚀 Localizeflow (Dự án hiện tại)
**Quy trình dịch tài liệu tự động gốc GitHub**  
Không cần cấu hình. Được lưu trữ. Đồng bộ tự động cho các dự án đa ngôn ngữ.  
→ https://localizeflow.com

- Tự động phát hiện thay đổi trong các tệp nguồn của bạn
- Dịch chỉ những phần thay đổi
- Mở PR cho từng ngôn ngữ
- Xây dựng trên nền tảng Co-op Translator (Azure OSS)


### **Co-op Translator (Microsoft Azure OSS)**

CLI chính thức của Azure OSS tự động hóa **dịch đa ngôn ngữ** cho nội dung Markdown + hình ảnh (OCR)  
**Tác động:** Cung cấp bản dịch cho các kho giáo dục của Microsoft với tổng cộng hơn 200k★, đảm bảo nội dung luôn được cập nhật ở trên 10 ngôn ngữ.

- Phát triển từ bản thử nghiệm PoC ban đầu → CLI Python cấp sản xuất
- Tích hợp Azure OpenAI + Azure AI Vision để tự động hóa dịch thuật + OCR
- Được sử dụng bởi các kho như:
  - [Generative AI for Beginners](https://github.com/microsoft/Generative-AI-for-beginners) (84k★)
  - [ML for Beginners](https://github.com/microsoft/ML-for-Beginners) (72k★)
  - [AI for Beginners](https://github.com/microsoft/AI-for-Beginners) (37k★)
  - [AI Agents for Beginners](https://github.com/microsoft/AI-Agents-for-Beginners) (17k★)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (3k★)
- Xuất hiện trong chương trình giới thiệu OSS **Open at Microsoft**
- Đạt giải **Microsoft AI MVP 2025**

[![Co-op Translator](https://github-readme-stats.vercel.app/api/pin/?username=Azure&repo=co-op-translator&bg_color=ffffff&title_color=0078D4&text_color=333333&border_color=c0d8f0&border_radius=10)](https://github.com/Azure/co-op-translator)

---

## Các Bài Thuyết Trình & Truyền Thông

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – Mở khóa khả năng tiếp cận đa ngôn ngữ với Co-op Translator](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – Lập kế hoạch và chuẩn bị phát triển giải pháp AI trên Azure](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## Các Giải Thưởng
- **Microsoft Most Valuable Professional (AI)** 2024–2025
- **Giải Nhất**, Lễ hội mã nguồn mở Đại học Inha (Co-op Translator)
- **Người chiến thắng**, Microsoft Korea Azurethon (hạng mục Prompt Engineering)
- **3 lần Blogger có lượt xem nhiều nhất**, Microsoft Educator Developer Blog

---

## Công Nghệ Sử Dụng
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

## Thống Kê & Hoạt Động
<details>
<summary>Xem Thống Kê GitHub</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 Kết nối với tôi
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![Email](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)