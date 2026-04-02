---
id: 202604022337
titel: Læse en fil sikkert i Python
sprog: python
tags: [programmering, python]
relateret: []
oprettet: 2026-04-02
---
## Hvad løser dette
Et simpelt og sikkert mønster til at læse indholdet af en tekstfil uden at skulle håndtere manuel åbning og lukning af filen.

## Kode
```python
def read_file(path):
    """Returnerer indholdet af en tekstfil som en streng."""
    with open(path, "r", encoding="utf-8") as f:
        return f.read()
