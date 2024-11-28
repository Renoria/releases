
# WEB Tier 02 Regex Checker

This regex pattern checks for specific terms related to "WEB Tier 02" releases.

## Regex Pattern

```regex
(\b(dB)\b|\b(Flights)\b|\b(MiU)\b|\b(monkee)\b|\b(MZABI)\b|\b(PHOENiX)\b|\b(playWEB)\b|\b(SbR)\b|\b(SMURF)\b|\b(TOMMY)\b|\b(XEBEC)\b)
```

## Explanation

- Each term is wrapped in a `\b` boundary for whole-word matching, ensuring it matches the term as a standalone word.
- The `|` operator allows matching any term at least once in a line.
