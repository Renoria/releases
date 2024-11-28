
# WEB Tier 01 Regex Checker

This regex pattern checks for specific terms related to "WEB Tier 01" releases.

## Regex Pattern

```regex
(\b(ABBIE)\b|\b(AJP69)\b|\b(APEX)\b|\b(BLUTONiUM)\b|\b(CMRG)\b|\b(CRFW)\b|\b(CRUD)\b|\b(FLUX)\b|\b(GNOME)\b|\b(HONE)\b|\b(KiNGS)\b|\b(Kitsune)\b|\b(NOSiViD)\b|\b(NTb)\b|\b(NTG)\b|\b(SiC)\b|\b(TEPES)\b)
```

## Explanation

- Each term is wrapped in a `\b` boundary for whole-word matching, ensuring it matches the term as a standalone word.
- The `|` operator allows matching any term at least once in a line.
