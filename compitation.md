# Language Proximity Analysis — Build Guide

Ten dokument opisuje **jak poprawnie zbudować aplikację** z użyciem **PyInstaller**  
(w szczególności **plik wykonywalny na Windows**).

Projekt **nie wspiera cross-kompilacji** (Linux → Windows).

---

## Wymagania ogólne

### System operacyjny
- **Windows** – do budowy pliku `.exe`
- Linux / macOS – tylko do developmentu i testów

>  EXE musi być budowane **na systemie użytkowym**.

## Kompilacja apki
### Odpal venv
- .venv\Scripts\activate
### Zkompiluj 
- python -m PyInstaller language_proximity_analysis.spec

