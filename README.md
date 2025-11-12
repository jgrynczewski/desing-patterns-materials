# Design Patterns - Materiały szkoleniowe

## 🚀 Szybki start (bez instalacji)

Kliknij przycisk poniżej, żeby uruchomić notebooki w przeglądarce:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jgrynczewski/desing-patterns-materials/main)

**Uwaga**: Pierwsze uruchomienie może potrwać 5-10 minut (budowanie środowiska). Kolejne uruchomienia będą szybsze.

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
pip install jupyterlab
pip install -r requirements.txt
jupyter lab
```

**Opcja 2: ZIP**
1. Pobierz [ZIP z tego linku](https://github.com/jgrynczewski/desing-patterns-materials/archive/refs/heads/main.zip)
2. Rozpakuj
3. Otwórz terminal w folderze `desing-patterns-materials-main`
4. Uruchom:
```bash
pip install jupyterlab
pip install -r requirements.txt
jupyter lab
```

---

## ⚙️ Zależności

Większość notebooków używa tylko biblioteki standardowej Pythona. Kilka przykładów wymaga:
- `requests` - HTTP client (przykłady Facade)
- `sqlalchemy` - ORM (przykłady Builder)

Wszystkie zależności instalują się automatycznie z `requirements.txt`.
