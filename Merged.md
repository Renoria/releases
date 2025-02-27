## ✨ Merged

This section merges **Movies** and **TV Shows** regexes together for a more streamlined experience, ideal with apps like [**Fusion**](https://discord.gg/UkgaxnbGpr) and [**Omni**](https://omni.stkc.win). It represents my personal recommendation and setup.

> [!Note]  
> - Some groups were **bumped a tier** to remove duplicates within the same release type.  
> - UHD & HD Bluray Tiers were **merged** since you can always tell from resolution.

> [!TIP]
> While this Merged list is great for TV and Movies, I **recommend** using the [**Anime**](Anime.md) regexes for anime releases.

---
### **Remux Tier 01** / 🍿1️⃣ / 📀1️⃣
  ```regex
  (?i)\bRemux\b.*\b(3L|BiZKiT|BLURANiUM|CiNEPHiLES|FraMeSToR|PmP|ZQ)\b|-BMF|-WiLDCAT
  ```
### **Remux Tier 02** / 🍿2️⃣ / 📀2️⃣
  ```regex
  (?i)\bRemux\b.*\b(Flights|NCmt|playBD|SiCFoI|SURFINBIRD|TEPES|decibeL|EPSiLON|HiFi|KRaLiMaRKo|PTer|TRiToN)\b
  ```
### **Remux Tier 03** / 🍿3️⃣ / 📀3️⃣
  ```regex
  (?i)\bRemux\b.*\b(iFT|NTb|PTP|SumVision|TOA)\b
  ```
---
### **Bluray Tier 01** / 💿1️⃣
  ```regex
  (?i)^(?=.*\bBlu[-_]?Ray\b)(?!.*\bRemux\b)(?!.*\bWEB[-_.]?(?:DL|Rip)\b)(?=.*(?:\b(?:BBQ|c0kE|Chotab|CRiSC|CtrlHD|D-Z0N3|Dariush|decibeL|DON|EbP|EDPH|Geek|LolHD|MainFrame|NCmt|NTb|PTer|TayTO|TDD|TnP|VietHD|W4NK3R|ZQ)\b|-BMF)).*
  ```
### **Bluray Tier 02** / 💿2️⃣
  ```regex
  (?i)^(?=.*\bBlu[-_]?Ray\b)(?!.*\bRemux\b)(?!.*\bWEB[-_.]?(?:DL|Rip)\b)(?=.*\b(?:EA|HiDt|HiSD|HQMUX|iFT|QOQ|SA89|sbR)\b).*
  ```
### **Bluray Tier 03** / 💿3️⃣
  ```regex
  (?i)^(?=.*\bBlu[-_]?Ray\b)(?!.*\bRemux\b)(?!.*\bWEB[-_.]?(?:DL|Rip)\b)(?=.*\b(?:BHDStudio|hallowed|HONE|LoRD|SPHD|WEBDV|playHD)\b).*
  ```
---
### **WEB Tier 01** / 🌐1️⃣
  ```regex
  (?i)^(?=.*\bWEB[-_.]?(?:DL|RIP)\b)(?=.*\b(?:ABBIE|AJP69|APEX|PAXA|PEXA|XEPA|BLUTONiUM|CasStudio|CMRG|CRFW|CRUD|CtrlHD|FLUX|GNOME|HONE|KiNGS|Kitsune|monkee|NOSiViD|NTb|NTG|QOQ|RTN|SiC|TEPES|T6D|TOMMY|ViSUM)\b).*
  ```
### **WEB Tier 02** / 🌐2️⃣
  ```regex
  (?i)^(?=.*\bWEB[-_.]?(?:DL|RIP)\b)(?=.*\b(?:3cTWeB|BTW|Chotab|Cinefeel|CiT|Coo7|dB|DEEP|END|ETHiCS|FC|Flights|iJP|iKA|iT00NZ|JETIX|KHN|KiMCHI|LAZY|MiU|MZABI|NPMS|NYH|orbitron|PHOENiX|playWEB|PSiG|ROCCaT|RTFM|SA89|SbR|SDCC|SIGMA|SMURF|SPiRiT|TVSmash|WELP|XEBEC|4KBEC|CEBEX)\b).*
  ```
### **WEB Tier 03** / 🌐3️⃣
  ```regex
  (?i)^(?=.*\bWEB[-_.]?(?:DL|RIP)\b)(?=.*\b(?:DRACULA|GNOMiSSiON|NINJACENTRAL|SiGMA|SLiGNOME|SwAgLaNdEr|T4H|ViSiON)\b).*
  ```
### **WEB Scene** / 🌐🎭
  ```regex
  (?i)^(?=.*\bWEB[-_.]?(?:DL|RIP)\b)(?=.*\b(?:DEFLATE|INFLATE)\b).*
  ```
