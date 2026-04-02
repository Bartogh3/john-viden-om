---
id: 202604022354
titel: Funktioner som værdier i Lua
sprog: lua
date: 2026-04-02
tags: [programmering, lua]
relateret: []
oprettet: 2026-04-02
---
## Hvad løser dette
Et mønster til at gemme funktioner i tabeller og kalde dem dynamisk.

## Kode
```lua
actions = {
    hej = function() print("Hej verden!") end,
    farvel = function() print("Farvel!") end
}

actions["hej"]()
```

## Forklaring
I Lua er funktioner første‑klasse‑værdier. Du kan gemme dem i tabeller, sende dem som argumenter og kalde dem efter behov.

## Eksempel på brug
```lua
kommandoer = {
    gem = function() print("Gemmer fil...") end,
    åbn = function() print("Åbner fil...") end
}

kommandoer["åbn"]()
```
Tags: #programmering #lua  
Links: [[MOC-Lua]]
