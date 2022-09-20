# Clash Premium Rules

## usage
```
rule-providers:
  edu: # edu resource websites
    type: http
    behavior: domain
    url: "https://cdn.jsdelivr.net/gh/kaminolee/ClashRules@master/edu.txt"
    path: ./ruleset/edu.yaml
    interval: 
  bilibili: # bilibili.com
    type: http
    behavior: domain
    url: "https://cdn.jsdelivr.net/gh/kaminolee/ClashRules@master/bilibili.txt"
    path: ./ruleset/bilibili.yaml
    interval: 86400
  porn: # porn websites
    type: http
    behavior: domain
    url: "https://cdn.jsdelivr.net/gh/kaminolee/ClashRules@master/porn.txt"
    path: ./ruleset/porn.yaml
    interval: 
  fix-proxy: # force proxy
    type: http
    behavior: domain
    url: "https://cdn.jsdelivr.net/gh/kaminolee/ClashRules@master/fix-proxy.txt"
    path: ./ruleset/fix-proxy.yaml
    interval: 86400
```
