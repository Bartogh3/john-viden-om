---
id: 202604022350
titel: Simpel fejlhåndtering med try/except
date: 2026-04-02
sprog: python
tags: [programmering, python]
relateret: []
oprettet: 2026-04-02
---
## Hvad løser dette
Et mønster til at fange og håndtere fejl uden at stoppe programmet.

## Kode
```python
try:
    tal = int(input("Indtast et tal: "))
    print(10 / tal)
except ValueError:
    print("Du skal indtaste et gyldigt tal.")
except ZeroDivisionError:
    print("Du kan ikke dividere med nul.")
```

## Forklaring
`try/except` gør det muligt at reagere på specifikke fejl. Det forbedrer robustheden og brugeroplevelsen.

## Eksempel på brug
```python
for x in ["5", "0", "hej"]:
    try:
        print(10 / int(x))
    except Exception as e:
        print(f"Fejl: {e}")
```
Tags: #programmering #python  
Links: [[MOC-Python]]
