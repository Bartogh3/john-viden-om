---
id: 202604022349
titel: Kombinér lister med zip()
date: 2026-04-02
sprog: python
tags: [programmering, python]
relateret: []
oprettet: 2026-04-02
---
## Hvad løser dette
Et mønster til at iterere over flere lister samtidigt og samle elementer parvist.

## Kode
```python
navne = ["Kim", "Sara", "Jonas"]
alder = [34, 29, 41]

for n, a in zip(navne, alder):
    print(f"{n} er {a} år gammel")
```

## Forklaring
`zip()` binder elementer fra flere sekvenser sammen i tuples. Det er nyttigt, når data hører sammen på tværs af lister.

## Eksempel på brug
```python
emails = ["kim@example.com", "sara@example.com", "jonas@example.com"]
for navn, mail in zip(navne, emails):
    print(f"Sender mail til {navn}: {mail}")
```
Tags: #programmering #python  
Links: [[MOC-Python]]
