
# Remux Tier 01 Regex Checker

This regex pattern checks for specific terms related to "Remux Tier 01" releases.

## Regex Pattern

```regex
(\b(3L)\b|\b(BiZKiT)\b|\b(BLURANiUM)\b|\b(CiNEPHiLES)\b|\b(FraMeSToR)\b|\b(PmP)\b|\b(WiLDCAT)\b|\b(ZQ)\b|-BMF\b)
```

## Explanation

- Each term is wrapped in a `\b` boundary for whole-word matching, where applicable.
- The `|` operator allows matching any term at least once in a line.
- `-BMF\b` is matched with a `-` prefix, following the format you specified.
