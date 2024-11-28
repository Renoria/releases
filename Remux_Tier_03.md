
# Remux Tier 03 Regex Checker

This regex pattern checks for specific terms related to "Remux Tier 03" releases.

## Regex Pattern

```regex
(\b(KRaLiMaRKo)\b|\b(decibeL)\b|\b(EPSiLON)\b|\b(HiFi)\b|\b(iFT)\b|\b(NTb)\b|\b(PTP)\b|\b(SumVision)\b|\b(TOA)\b|\b(TRiToN)\b)
```

## Explanation

- Each term is wrapped in a `\b` boundary for whole-word matching, ensuring it matches the term as a standalone word.
- The `|` operator allows matching any term at least once in a line.
