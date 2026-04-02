---
id: 202604022345
titel: Brug af enumerate til pæn iteration
date: 2026-04-02
sprog: python
tags: [programmering, python]
relateret: []
oprettet: 2026-04-02
---
## Hvad løser dette
Et mønster til at iterere over en liste, hvor du både får indeks og værdi uden at skulle holde styr på en manuel tæller.

## Kode
```python
frugter = ["æble", "banan", "pære"]

for i, frugt in enumerate(frugter, start=1):
    print(i, frugt)
```
## Forklaring
`enumerate()` giver dig både indeks og element i hvert loop. Det gør koden mere læsbar og fjerner behovet for at opdatere en tæller manuelt. `start=1` gør, at nummereringen begynder ved 1 i stedet for 0.

## Eksempel på brug
```python
for nummer, navn in enumerate(["Kim", "Sara", "Jonas"]):
    print(f"Deltager {nummer}: {navn}")
```
Tags: #programmering #python  
Links: [[MOC-Python]]
