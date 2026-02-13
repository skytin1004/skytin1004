![Header Banner](https://github.com/user-attachments/assets/e5c72b81-0bcb-403a-9efe-76d04991d303)

# ഹായ്, ഞാൻ മിൻസിയോക്ക് സോങ്

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?logo=githubsponsors&style=for-the-badge)](https://github.com/sponsors/skytin1004)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black&style=for-the-badge)](https://coff.ee/skytin1004)

**[Localizeflow](https://localizeflow.com) സ്ഥാപകൻ**

**Microsoft AI MVP • [Azure/co-op-translator](https://github.com/Azure/co-op-translator) എന്ന project's OSS മേൽനോട്ടಾಧಿಕാരി**

ഞാൻ വികസിപ്പിക്കുന്നത് വികസകർക്കു പ്രവർത്തന തടസ്സം ഒഴിവാക്കുന്ന ടൂളുകളെ കുറിച്ചാണ്.

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](./README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **പ്രാദേശികമായി ക്ലോൺ ചെയ്യാൻ താൽപ്പര്യമുണ്ടോ?**
>
> ഈ റിപോസിറ്ററിയിൽ 50-ലധികം ഭാഷാ വിവർത്തനങ്ങൾ ഉൾപ്പെടുത്തി, ഇത് ഡൗൺലോഡ് വലുപ്പം വളരെ വർധിപ്പിക്കുന്നു. വിവർത്തനങ്ങൾ കൂടാതെ ക്ലോൺ ചെയ്യുന്നതിന് sparse checkout ഉപയോഗിക്കുക:
>
> **Bash / macOS / Linux:**
> ```bash
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
>
> **CMD (Windows):**
> ```cmd
> git clone --filter=blob:none --sparse https://github.com/skytin1004/skytin1004.git
> cd skytin1004
> git sparse-checkout set --no-cone "/*" "!translations" "!translated_images"
> ```
>
> ഇത് കോഴ്സ് പൂർത്തിയാക്കാൻ ആവശ്യമായ എല്ലാം വളരെ വേഗത്തിൽ ഡൗൺലോഡ് ചെയ്യാനുള്ള വഴിയാണ്.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## ഞാൻ പ്രാദേശീകരണം വികസിപ്പിക്കുന്നത് എന്തിനാണെന്നു

ചെറിയ ടീമുകൾ കൂടെ ജെനറൽ യൂസേഴ്സിനെ സേവിക്കാൻ ആഗ്രഹിക്കുന്നു. പക്ഷേ അവർ പ്രാദേശീകരണം നടത്താറില്ല.

വിവർത്തനം വിലകൂടുതലാണ് കൊണ്ട് അല്ല.
എ.ഐ. ക്ഷാമം ഉള്ളതിനാലും അല്ല.

പറഞ്ഞാൽ പ്രാദേശീകരണം തുടങ്ങുമെങ്കിലും അത് ഉടനെ ഒരു പ്രവർത്തന പദ്ധതി ആയിരിക്കും.

- i18n ഘടനാ തീരുമാനങ്ങൾ
- YAML കോൺഫിഗറേഷൻസ്
- വിവർത്തന പൈപ്പ്ലൈനുകൾ
- അവലോകന പ്രവർത്തനങ്ങൾ
- പരിപാലന ബുദ്ധിമുട്ടുകൾ

അതുകൊണ്ടാണ് അവർ വൈകിപ്പിക്കുന്നതും അല്ലെങ്കിൽ ഒരുമിച്ച് തുടങ്ങാതിരിക്കുന്നതും.

ദോത ухода Localizeflow-നു വെച്ചുള്ള എന്റെ ശ്രമം ആ തടസ്സം നീക്കുകയാണ്.

---

## 🚀 Localizeflow

GitHub-സ്വദേശീയ ഡോക്യുമെന്റേഷൻ പ്രാദേശീകരണം.
ഒരിക്കൽ ഇൻസ്റ്റാൾ ചെയ്യുക. YAML ഇല്ല. API കീകൾ ഇല്ല. ഡാഷ്‌ബോർഡുകൾ ഇല്ല.

- ഉറവിട മാറ്റങ്ങൾ കണ്ടെത്തുന്നു
- മാറ്റിയതിനെ മാത്രം വിവർത്തനം ചെയ്യുന്നു
- പുൾ റിക്വസ്റ്റുകൾ സ്വയം തുറക്കുന്നു
- മാനേജുചെയ്യുന്ന ഇൻഫ്രാസ്ട്രക്ചറിൽ പ്രവർത്തിക്കുന്നു

ഉദ്ദേശിച്ചത്:
- വലിയ OOSS/പൊതുസാഹചര്യ മേൽനോട്ടാധികാരികൾക്ക്
- ഇൻഡി ഡെവലപ്പർമാർക്ക്
- ആരംഭ ഘട്ട സ്റ്റാർട്ടപ്പുകൾക്ക്

→ https://localizeflow.com

---

## 🛠 Co-op Translator (Azure OSS)

Azure/co-op-translator കൈകാര്യം ചെയ്യുന്നവൻ

ബഹുഭാഷാ മാർക്ക്ഡൗൺ + ചിത്രം വിവർത്തനം ഓട്ടോമേറ്റുചെയ്യുന്ന CLI.

ഉപയോഗിക്കുന്നത്:
- Generative AI for Beginners
- ML for Beginners
- AI for Beginners
- കൂടാതെ മറ്റ് Microsoft OSS റിപോസിറ്ററികൾ

---

## വക്തൃത്വങ്ങളും മീഡിയയും

<p align="left">
  <a href="https://www.youtube.com/watch?v=jX_swfH_KNU">
    <img src="https://img.youtube.com/vi/jX_swfH_KNU/0.jpg" width="400" />
  </a>
  <a href="https://www.youtube.com/watch?v=Zl_IFvrKaaY">
    <img src="https://img.youtube.com/vi/Zl_IFvrKaaY/0.jpg" width="400" />
  </a>
</p>

- [Open at Microsoft – Co-op Translator ഉപയോഗിച്ച് ബഹുഭാഷാ ആക്സസിബിലിറ്റി തുറക്കൽ](https://www.youtube.com/watch?v=jX_swfH_KNU)  
- [Microsoft Learn Live – Azure-യിൽ AI സൊല്യൂഷനുകൾ വികസിപ്പിക്കാനുള്ള പദ്ധതിയും തയ്യാറെടുപ്പും](https://www.youtube.com/watch?v=Zl_IFvrKaaY)  

---

## ടെക് സ്റ്റാക്ക്
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

## സ്ഥിതിവിവരങ്ങളും പ്രവർത്തനങ്ങളും
<details>
<summary>GitHub സ്ഥിതിവിവരങ്ങൾ കാണുക</summary>

[![Stats](https://github-readme-stats.vercel.app/api?username=skytin1004&show_icons=true&theme=tokyonight&rank_icon=github)](https://github.com/anuraghazra/github-readme-stats)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=skytin1004&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
</details>
---

## 📫 എനിക്ക് ബന്ധപ്പെടുക
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/song-ai/)  
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&style=for-the-badge&logoColor=white)](https://x.com/skytin1004)  
[![Portfolio](https://img.shields.io/badge/Portfolio-343a40?logo=GitHub&style=for-the-badge&logoColor=white)](https://skytin1004.github.io/)  
[![Tech Community](https://img.shields.io/badge/Microsoft_Tech_Community-0078D4?logo=microsoft&style=for-the-badge&logoColor=white)](https://techcommunity.microsoft.com/users/minseok_song/2076234)  
[![Email](https://img.shields.io/badge/Email-minseok.song@mssong.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minseok.song@mssong.com)