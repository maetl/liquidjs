---
title: replace_first
---

Replaces only the first occurrence of the first argument in a string with the second argument.

Input
```liquid
{{ "Take my protein pills and put my helmet on" | replace_first: "my", "your" }}
```

Output
```text
Take your protein pills and put my helmet on
```
