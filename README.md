# Design Patterns - Materiały szkoleniowe

Kompleksowe materiały do nauki wzorców projektowych, zasad SOLID i GRASP w Pythonie.

## 🚀 Szybki start (Binder - bez instalacji)

Kliknij przycisk poniżej, żeby uruchomić notebooki w przeglądarce:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jgrynczewski/desing-patterns-materials/main)

**Uwaga**: Pierwsze uruchomienie może potrwać 5-10 minut (budowanie środowiska). Kolejne uruchomienia będą szybsze.

**Dla uczestników szkoleń**: Binder działa świetnie do szybkich testów, ale dla 3-dniowego szkolenia zalecamy pracę lokalną (poniżej).

---

## 💻 Praca lokalna (zalecane)

### Wymagania
- Python 3.10 lub nowszy
- pip
- Jupyter Lab lub Jupyter Notebook

### Instalacja

**Opcja 1: Git**
```bash
git clone https://github.com/jgrynczewski/desing-patterns-materials.git
cd desing-patterns-materials
pip install -r requirements.txt
jupyter lab
```

**Opcja 2: ZIP**
1. Pobierz [ZIP z tego linku](https://github.com/jgrynczewski/desing-patterns-materials/archive/refs/heads/main.zip)
2. Rozpakuj
3. Otwórz terminal w folderze `desing-patterns-materials-main`
4. Uruchom:
```bash
pip install -r requirements.txt
jupyter lab
```

---

## 📂 Struktura materiałów

### Fundamenty
- **0_intro/** - Type annotations, duck typing
- **1_oop/** - Enkapsulacja, abstrakcja, dziedziczenie, polimorfizm

### Zasady projektowania
- **2_grasp/** - Zasady GRASP (Low Coupling, High Cohesion, Creator, Information Expert, Polymorphism, Controller, Pure Fabrication, Indirection, Protected Variations)
- **3_interface/** - Interfejsy w Pythonie
- **4_solid/** - Zasady SOLID (SRP, OCP, LSP, ISP, DIP)

### Wzorce projektowe
- **patterns/** - Implementacje wzorców projektowych z przykładami

---

## ⚙️ Zależności

Większość notebooków używa tylko biblioteki standardowej Pythona. Kilka przykładów wymaga:
- `requests` - HTTP client (przykłady Facade)
- `sqlalchemy` - ORM (przykłady Builder)

Wszystkie zależności instalują się automatycznie z `requirements.txt`.

---

## 📝 Wskazówki dla uczestników szkoleń

1. **Dzień 1**: Przetestuj Binder (15 min), potem przejdź na lokalną pracę
2. **Zapisuj regularnie**: `Ctrl+S` w Jupyter
3. **Pobierz zmiany**: `File > Download` w Jupyter lub `git pull` lokalnie
4. **Problemy?**: Binder zawsze działa jako backup

---

## 📖 Licencja i kontakt

Materiały szkoleniowe - wykorzystanie edukacyjne.
