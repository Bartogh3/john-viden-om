---
id: 202604022348
titel: Listeforståelse i Python
date: 2026-04-02
sprog: python
tags: [programmering, python]
relateret: []
oprettet: 2026-04-02
---
## Hvad løser dette
Et kompakt mønster til at oprette nye lister ud fra eksisterende data uden brug af eksplicitte loops.

## Kode
```python
kvadrater = [x**2 for x in range(5)]
```

## Forklaring
Listeforståelse gør koden kortere og mere læsbar. Her genereres en liste med kvadrater af tallene 0–4.

## Eksempel på brug
```python
navne = ["Kim", "Sara", "Jonas"]
store = [n.upper() for n in navne]
print(store)
```
Tags: #programmering #python  
Links: [[MOC-Python]]
