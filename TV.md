# TV Shows

**All TV Shows** is the parent group that includes every Trash recommended release group, regardless of its format. It is divided into three main subsets:

- **Remux Tiers**
- **HD Bluray Tiers**
- **WEB Tiers**

Each subset is further organized into subtiers for more detailed categorization.

---

## All TV Shows

  ```regex
  \b(BLURANiUM|FraMeSToR|PmP|decibeL|EPSiLON|HiFi|KRaLiMaRKo|playBD|PTer|SiCFoI|TRiToN|Chotab|CtrlHD|DON|EbP|NTb|SA89|sbR|ABBiE|AJP69|APEX|PAXA|PEXA|XEPA|CasStudio|CRFW|FLUX|HONE|KiNGS|Kitsune|monkee|NOSiViD|NTG|QOQ|RTN|SiC|T6D|TOMMY|ViSUM|3cTWeB|BLUTONiUM|BTW|Cinefeel|CiT|CMRG|Coo7|dB|DEEP|END|ETHiCS|FC|Flights|GNOME|iJP|iKA|iT00NZ|JETIX|KHN|KiMCHI|LAZY|MiU|MZABI|NPMS|NYH|orbitron|PHOENiX|playWEB|PSiG|ROCCaT|RTFM|SbR|SDCC|SIGMA|SMURF|SPiRiT|TEPES|TVSmash|WELP|XEBEC|4KBEC|CEBEX|DRACULA|NINJACENTRAL|SLiGNOME|SwAgLaNdEr|T4H|ViSiON|DEFLATE|INFLATE)\b|-BMF
```
---

## Remux Tiers

  ```regex
  \b(BLURANiUM|FraMeSToR|PmP|decibeL|EPSiLON|HiFi|KRaLiMaRKo|playBD|PTer|SiCFoI|TRiToN)\b|-BMF
  ```

### Subtiers

**Remux Tier 01**
  ```regex
  \b(BLURANiUM|FraMeSToR|PmP)\b|-BMF
  ```
**Remux Tier 02**
  ```regex
  \b(decibeL|EPSiLON|HiFi|KRaLiMaRKo|playBD|PTer|SiCFoI|TRiToN)\b
  ```

---

## HD Bluray Tiers

  ```regex
  \b(Chotab|CtrlHD|DON|EbP|NTb|PTer|SA89|sbR)\b
  ```

### Subtiers

**HD Bluray Tier 01**
  ```regex
  \b(Chotab|CtrlHD|DON|EbP|NTb|PTer)\b
  ```
**HD Bluray Tier 02**
  ```regex
  \b(SA89|sbR)\b
  ```

---

## WEB Tiers

  ```regex
  \b(ABBiE|AJP69|APEX|PAXA|PEXA|XEPA|CasStudio|CRFW|CtrlHD|FLUX|HONE|KiNGS|Kitsune|monkee|NOSiViD|NTb|NTG|QOQ|RTN|SiC|T6D|TOMMY|ViSUM|3cTWeB|BLUTONiUM|BTW|Chotab|Cinefeel|CiT|CMRG|Coo7|dB|DEEP|END|ETHiCS|FC|Flights|GNOME|iJP|iKA|iT00NZ|JETIX|KHN|KiMCHI|LAZY|MiU|MZABI|NPMS|NYH|orbitron|PHOENiX|playWEB|PSiG|ROCCaT|RTFM|SA89|SbR|SDCC|SIGMA|SMURF|SPiRiT|TEPES|TVSmash|WELP|XEBEC|4KBEC|CEBEX|DRACULA|NINJACENTRAL|SLiGNOME|SwAgLaNdEr|T4H|ViSiON|DEFLATE|INFLATE)\b
  ```

### Subtiers

**WEB Tier 01**
  ```regex
  \b(ABBiE|AJP69|APEX|PAXA|PEXA|XEPA|CasStudio|CRFW|CtrlHD|FLUX|HONE|KiNGS|Kitsune|monkee|NOSiViD|NTb|NTG|QOQ|RTN|SiC|T6D|TOMMY|ViSUM)\b
  ```
**WEB Tier 02**
  ```regex
  \b(3cTWeB|BLUTONiUM|BTW|Chotab|Cinefeel|CiT|CMRG|Coo7|dB|DEEP|END|ETHiCS|FC|Flights|GNOME|iJP|iKA|iT00NZ|JETIX|KHN|KiMCHI|LAZY|MiU|MZABI|NPMS|NYH|orbitron|PHOENiX|playWEB|PSiG|ROCCaT|RTFM|SA89|SbR|SDCC|SIGMA|SMURF|SPiRiT|TEPES|TVSmash|WELP|XEBEC|4KBEC|CEBEX)\b
  ```
**WEB Tier 03**
  ```regex
  \b(DRACULA|NINJACENTRAL|SLiGNOME|SwAgLaNdEr|T4H|ViSiON)\b
  ```
**WEB Scene**
  ```regex
  \b(DEFLATE|INFLATE)\b
  ```

## Explanation

- Each term is wrapped in a `\b` boundary for whole-word matching, ensuring it matches the term as a standalone word.
- The `|` operator allows matching any term at least once in a line.
