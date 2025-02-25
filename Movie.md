# Movies

**All Movies** is the parent group that includes every Trash recommended release group, regardless of its format. It is divided into four main subsets:

- **Remux Tiers**
- **UHD Bluray Tiers**
- **HD Bluray Tiers**
- **WEB Tiers**

Each subset is further organized into subtiers for more detailed categorization.

---

## All Movies

  ```regex
  \b(3L|BiZKiT|BLURANiUM|CiNEPHiLES|FraMeSToR|PmP|ZQ|Flights|NCmt|playBD|SiCFoI|SURFINBIRD|TEPES|decibeL|EPSiLON|HiFi|iFT|KRaLiMaRKo|NTb|PTP|SumVision|TOA|TRiToN|CtrlHD|MainFrame|DON|W4NK3R|HQMUX|BHDStudio|hallowed|HONE|PTer|SPHD|WEBDV|BBQ|c0kE|Chotab|CRiSC|D-Z0N3|Dariush|EbP|EDPH|Geek|LolHD|TayTO|TDD|TnP|VietHD|EA|HiDt|HiSD|QOQ|SA89|sbR|LoRD|playHD|ABBIE|AJP69|APEX|PAXA|PEXA|XEPA|BLUTONiUM|CMRG|CRFW|CRUD|FLUX|GNOME|KiNGS|Kitsune|NOSiViD|NTG|SiC|dB|MiU|monkee|MZABI|PHOENiX|playWEB|SbR|SMURF|TOMMY|XEBEC|4KBEC|CEBEX)\b|-BMF|-WiLDCAT
  ```

---

## Remux Tiers

  ```regex
  \b(3L|BiZKiT|BLURANiUM|CiNEPHiLES|FraMeSToR|PmP|ZQ|Flights|NCmt|playBD|SiCFoI|SURFINBIRD|TEPES|decibeL|EPSiLON|HiFi|iFT|KRaLiMaRKo|NTb|PTP|SumVision|TOA|TRiToN)\b|-BMF|-WiLDCAT
  ```

### Subtiers

**Remux Tier 01**
  ```regex
  \b(3L|BiZKiT|BLURANiUM|CiNEPHiLES|FraMeSToR|PmP|ZQ)\b|-BMF|-WiLDCAT
  ```
**Remux Tier 02**
  ```regex
  \b(Flights|NCmt|playBD|SiCFoI|SURFINBIRD|TEPES)\b
  ```
**Remux Tier 03**
  ```regex
  \b(decibeL|EPSiLON|HiFi|iFT|KRaLiMaRKo|NTb|PTP|SumVision|TOA|TRiToN)\b
  ```

---

## UHD Bluray Tiers

  ```regex
  \b(CtrlHD|MainFrame|DON|W4NK3R|HQMUX|BHDStudio|hallowed|HONE|PTer|SPHD|WEBDV)\b
  ```

### Subtiers

**UHD Bluray Tier 01**
  ```regex
  \b(CtrlHD|MainFrame|DON|W4NK3R)\b
  ```
**UHD Bluray Tier 02**
  ```regex
  \b(HQMUX)\b
  ```
**UHD Bluray Tier 03**
  ```regex
  \b(BHDStudio|hallowed|HONE|PTer|SPHD|WEBDV)\b
  ```

---

## HD Bluray Tiers

  ```regex
  \b(BBQ|c0kE|Chotab|CRiSC|CtrlHD|D-Z0N3|Dariush|decibeL|DON|EbP|EDPH|Geek|LolHD|NCmt|PTer|TayTO|TDD|TnP|VietHD|ZQ|EA|HiDt|HiSD|iFT|NTb|QOQ|SA89|sbR|BHDStudio|hallowed|HONE|LoRD|playHD|SPHD|W4NK3R)\b|-BMF
  ```

### Subtiers

**HD Bluray Tier 01**
  ```regex
  \b(BBQ|c0kE|Chotab|CRiSC|CtrlHD|D-Z0N3|Dariush|decibeL|DON|EbP|EDPH|Geek|LolHD|NCmt|PTer|TayTO|TDD|TnP|VietHD|ZQ)\b|-BMF
  ```
**HD Bluray Tier 02**
  ```regex
  \b(EA|HiDt|HiSD|iFT|NTb|QOQ|SA89|sbR)\b
  ```
**HD Bluray Tier 03**
  ```regex
  \b(BHDStudio|hallowed|HONE|LoRD|playHD|SPHD|W4NK3R)\b
  ```

---

## WEB Tiers

  ```regex
  \b(ABBIE|AJP69|APEX|PAXA|PEXA|XEPA|BLUTONiUM|CMRG|CRFW|CRUD|FLUX|GNOME|HONE|KiNGS|Kitsune|NOSiViD|NTb|NTG|SiC|TEPES|dB|Flights|MiU|monkee|MZABI|PHOENiX|playWEB|SbR|SMURF|TOMMY|XEBEC|4KBEC|CEBEX)\b
  ```

### Subtiers

**WEB Tier 01**
  ```regex
  \b(ABBIE|AJP69|APEX|PAXA|PEXA|XEPA|BLUTONiUM|CMRG|CRFW|CRUD|FLUX|GNOME|HONE|KiNGS|Kitsune|NOSiViD|NTb|NTG|SiC|TEPES)\b
  ```
**WEB Tier 02**
  ```regex
  \b(dB|Flights|MiU|monkee|MZABI|PHOENiX|playWEB|SbR|SMURF|TOMMY|XEBEC|4KBEC|CEBEX)\b
  ```
**WEB Tier 03**
  ```regex
  \b(GNOMiSSiON|NINJACENTRAL|ROCCaT|SiGMA|SLiGNOME|SwAgLaNdEr)\b
  ```

## Explanation

- Each term is wrapped in a `\b` boundary for whole-word matching, ensuring it matches the term as a standalone word.
- The `|` operator allows matching any term at least once in a line.
