---
id: 202604022353
titel: Iteration over tabeller med pairs()
date: 2026-04-02
sprog: lua
tags: [programmering, lua]
relateret: []
oprettet: 2026-04-02
---
## Hvad løser dette
Et mønster til at gennemløbe alle nøgler og værdier i en tabel.

## Kode
```lua
data = {navn = "Kim", alder = 34, by = "Slagelse"}

for key, value in pairs(data) do
    print(key, value)
end
```

## Forklaring
`pairs()` returnerer hvert nøgle‑værdi‑par i tabellen. Det er nyttigt til dynamiske datastrukturer, hvor du ikke kender nøglerne på forhånd.

## Eksempel på brug
```lua
indstillinger = {tema = "mørk", autosave = true}
for k, v in pairs(indstillinger) do
    print("Indstilling:", k, "=", v)
end
```
Tags: #programmering #lua  
Links: [[MOC-Lua]]
