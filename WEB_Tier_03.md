
# WEB Tier 03 Regex Checker

This regex pattern checks for specific terms related to "WEB Tier 03" releases.

## Regex Pattern

```regex
(\b(GNOMiSSiON)\b|\b(NINJACENTRAL)\b|\b(ROCCaT)\b|\b(SiGMA)\b|\b(SLiGNOME)\b|\b(SwAgLaNdEr)\b)
```

## Explanation

- Each term is wrapped in a `\b` boundary for whole-word matching, ensuring it matches the term as a standalone word.
- The `|` operator allows matching any term at least once in a line.
