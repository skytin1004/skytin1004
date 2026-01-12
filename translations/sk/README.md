<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "15f14ebaa9879ea2be727ca61fd489c8",
  "translation_date": "2026-01-12T12:33:29+00:00",
  "source_file": "README.md",
  "language_code": "sk"
}
-->
![Header Banner](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# Ahoj, som Minseok Song!

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**Tvorca [Localizeflow](https://localizeflow.com)**

**Microsoft AI MVP • OSS správca [Azure/co-op-translator](https://github.com/Azure/co-op-translator)**

Milujem vytvárať nástroje pre vývojárov poháňané AI, open-source, ktoré škálujú globálne a premieňajú koncepty v počiatočnej fáze na produkčne pripravené riešenia s reálnym dopadom.

### 🌐 Podpora viacerých jazykov

#### Podporované [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabčina](../ar/README.md) | [Bengálčina](../bn/README.md) | [Bulharčina](../bg/README.md) | [Barmský (Myanmar)](../my/README.md) | [Čínština (zjednodušená)](../zh/README.md) | [Čínština (tradičná, Hong Kong)](../hk/README.md) | [Čínština (tradičná, Macao)](../mo/README.md) | [Čínština (tradičná, Taiwan)](../tw/README.md) | [Chorvátčina](../hr/README.md) | [Čeština](../cs/README.md) | [Dánčina](../da/README.md) | [Holandčina](../nl/README.md) | [Estónčina](../et/README.md) | [Fínčina](../fi/README.md) | [Francúzština](../fr/README.md) | [Nemčina](../de/README.md) | [Gréčtina](../el/README.md) | [Hebrejčina](../he/README.md) | [Hindčina](../hi/README.md) | [Maďarčina](../hu/README.md) | [Indonézština](../id/README.md) | [Taliančina](../it/README.md) | [Japončina](../ja/README.md) | [Kannadčina](../kn/README.md) | [Kórejčina](../ko/README.md) | [Litovčina](../lt/README.md) | [Malajčina](../ms/README.md) | [Malayalam](../ml/README.md) | [Maráthčina](../mr/README.md) | [Nepálčina](../ne/README.md) | [Nigerijský pidžin](../pcm/README.md) | [Nórčina](../no/README.md) | [Perzština (Farsi)](../fa/README.md) | [Poľština](../pl/README.md) | [Portugalčina (Brazília)](../br/README.md) | [Portugalčina (Portugalsko)](../pt/README.md) | [Pandžábčina (Gurmukhi)](../pa/README.md) | [Rumunčina](../ro/README.md) | [Ruština](../ru/README.md) | [Srbčina (cyrilika)](../sr/README.md) | [Slovenčina](./README.md) | [Slovinčina](../sl/README.md) | [Španielčina](../es/README.md) | [Svahilčina](../sw/README.md) | [Švédčina](../sv/README.md) | [Tagalog (Filipínska)](../tl/README.md) | [Tamilčina](../ta/README.md) | [Telugčina](../te/README.md) | [Thajčina](../th/README.md) | [Turečtina](../tr/README.md) | [Ukrajinčina](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamčina](../vi/README.md)

> **Preferujete klonovať lokálne?**

> Tento repozitár obsahuje viac ako 50 jazykových prekladov, čo výrazne zväčšuje veľkosť sťahovania. Ak chcete klonovať bez prekladov, použite sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Toto vám poskytne všetko potrebné na dokončenie kurzu s omnoho rýchlejším sťahovaním.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

---

## Kľúčový projekt

### 🚀 Localizeflow (aktuálny projekt)
**Nástroj na automatizovaný preklad dokumentácie natívne v GitHub**  
Žiadna konfigurácia. Hostované. Automatická synchronizácia pre viacjazyčné projekty.  
→ https://localizeflow.com

- Automaticky detekuje zmeny vo vašich zdrojových súboroch
- Prekladá len to, čo sa zmenilo
- Otvára pull requesty pre každý jazyk
- Postavené na základe Co-op Translator (Azure OSS)

### **Co-op Translator (Microsoft Azure OSS)**

Oficiálny Azure OSS CLI, ktorý automatizuje **viacjazyčné preklady** pre Markdown + obsah obrázkov (OCR)  
**Dopad:** Poháňa preklady pre vzdelávacie repozitáre Microsoft celkom s viac ako 200k★, zabezpečujúc vždy aktuálny obsah v 10+ jazykoch.

- Vyvinuté od počiatočného PoC až po produkčný Python CLI
- Integrované Azure OpenAI + Azure AI Vision pre preklad + automatizáciu OCR
- Používané v repozitároch ako:
  - [Generative AI for Beginners](https://github.com/microsoft/Generative-AI-for-beginners) (84k★)
  - [ML for Beginners](https://github.com/microsoft/ML-for-Beginners) (72k★)
  - [AI for Beginners](https://github.com/microsoft/AI-for-Beginners) (37k★)
  - [AI Agents for Beginners](https://github.com/microsoft/AI-Agents-for-Beginners) (17k★)
  - [PhiCookbook](https://github.com/microsoft/PhiCookbook) (3k★)
- Prezentované v showcase **Open at Microsoft** OSS
- Ocenené ako **Microsoft AI MVP 2025**

[![Co-op Translator](https://github-readme-stats.vercel.app/api/pin/?username=Azure&repo=co-op-translator&bg_color=ffffff&title_color=0078D4&text_color=333333&border_color=c0d8f0&border_radius=10)](https://github.com/Azure/co-op-translator)

---

## Prednášky a média

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – Odomykanie viacjazyčnej prístupnosti pomocou Co-op Translator](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – Plánujte a pripravte sa na vývoj AI riešení na Azure](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## Ocenenia
- **Microsoft Most Valuable Professional (AI)** 2024–2025
- **1. miesto**, Inha University Open Source Festival (Co-op Translator)
- **Víťaz**, Microsoft Korea Azurethon (kategória Prompt Engineering)
- **3× Najsledovanejší bloger**, Microsoft Educator Developer Blog

---

## Technológie
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

## Štatistiky & aktivita
<details>
<summary>Zobraziť GitHub štatistiky</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 Spojte sa so mnou
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![Email](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)