
# Remux Tier 02 Regex Checker

This regex pattern checks for specific terms related to "Remux Tier 02" releases.

## Regex Pattern

```regex
(\b(Flights)\b|\b(NCmt)\b|\b(playBD)\b|\b(SiCFoI)\b|\b(SURFINBIRD)\b|\b(TEPES)\b)
```

## Explanation

- Each term is wrapped in a `\b` boundary for whole-word matching, ensuring it matches the term as a standalone word.
- The `|` operator allows matching any term at least once in a line.
