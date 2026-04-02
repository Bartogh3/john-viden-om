---
id: 202604030129
titel: MOC Lua Python
date: 2026-04-03
---
# MOC-Lua-Python

## Formål

Denne fælles oversigt binder Lua- og Python-noterne sammen, så du hurtigt kan sammenligne syntaks og mønstre mellem sprogene.

## Python-noter

- [[listeforståelse-i-python]]
- [[kombiner-lister-med-zip]]
- [[brug-af-enumerate-til-paen-iteration]]
- [[simpel-fejlhåndtering-med-try-except]]

## Lua-noter

- [[iteration-over-tabeller-med-pairs]]
- [[funktioner-som-vaerdier-i-lua]]
- [[fejlhåndtering-med-pcall]]

## Sammenligningstemaer

| Emne                | Python                    | Lua                   |
| ------------------- | ------------------------- | --------------------- |
| Iteration           | `for i, v in enumerate()` | `for k, v in pairs()` |
| Fejlhåndtering      | `try/except`              | `pcall()`             |
| Funktioner som data | Lambda / def              | Funktionstabeller     |

## Næste skridt

Tilføj noter om:

- Forskelle i datatyper
- Moduler og imports
- Performance og ressourcestyring

Tags: #programmering #lua #python