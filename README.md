# Edu Rule For Clash Premium

## usage

```
rule-providers:
  edu:
    type: http
    behavior: ipcidr
    url: "https://cdn.jsdelivr.net/gh/kamino-space/EduRules@master/edu.txt"
    path: ./ruleset/edu.yaml
    interval: 86400
```