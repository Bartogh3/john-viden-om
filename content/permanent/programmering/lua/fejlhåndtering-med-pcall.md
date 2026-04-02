---
id: 202604022355
titel: Fejlhåndtering med pcall()
date: 2026-04-02
sprog: lua
tags: [programmering, lua]
relateret: []
oprettet: 2026-04-02
---
## Hvad løser dette
Et mønster til at fange fejl uden at stoppe programmet.

## Kode
```lua
function divider(a, b)
    return a / b
end

status, resultat = pcall(divider, 10, 0)
```

## Forklaring
`pcall()` (protected call) returnerer `true` og resultatet, hvis funktionen lykkes, ellers `false` og fejlbeskeden. Det gør det nemt at håndtere fejl uden at crashe.

## Eksempel på brug
```lua
ok, res = pcall(divider, 10, 2)
if ok then
    print("Resultat:", res)
else
    print("Fejl:", res)
end
```
Tags: #programmering #lua  
Links: [[MOC-Lua]]
