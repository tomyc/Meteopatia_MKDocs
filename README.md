# Meteoropatia - Kompleksowy Przewodnik

![Meteoropatia](https://img.shields.io/badge/Meteoropatia-Przewodnik-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![MkDocs](https://img.shields.io/badge/MkDocs-Material-blue)
![Language](https://img.shields.io/badge/Language-Polish-red)

## 🌦️ O projekcie

**Meteoropatia - Kompleksowy Przewodnik** to naukowe kompendium wiedzy na temat zarządzania wrażliwością meteorologiczną. Portal zawiera praktyczne protokoły, strategie i narzędzia oparte na najnowszych badaniach naukowych, dostosowane do polskiego klimatu i stylu życia.

## 🚀 Portal online

**Portal jest dostępny pod adresem:** [https://tomyc.github.io/Meteopatia_MKDocs](https://tomyc.github.io/Meteopatia_MKDocs)

## 📋 Zawartość portalu

### Główne sekcje:

1. **[Czym jest meteoropatia](https://tomyc.github.io/Meteopatia_MKDocs/meteoropatia/)** - Podstawy naukowe i mechanizmy neurofizjologiczne
2. **[Sposoby leczenia](https://tomyc.github.io/Meteopatia_MKDocs/sposoby-leczenia/)** - Interwencje niefarmakologiczne oparte na dowodach
3. **[Odżywianie](https://tomyc.github.io/Meteopatia_MKDocs/odzywienie/)** - Dieta przeciwzapalna dla meteoropatów
4. **[Ćwiczenia](https://tomyc.github.io/Meteopatia_MKDocs/cwiczenia/)** - Protokoły aktywności fizycznej
5. **[Higiena życia](https://tomyc.github.io/Meteopatia_MKDocs/higiena-zycia/)** - Optymalizacja snu i środowiska
6. **[Narzędzia wspierające](https://tomyc.github.io/Meteopatia_MKDocs/narzedzia/)** - Aplikacje i technologie
7. **[Adaptacje sezonowe](https://tomyc.github.io/Meteopatia_MKDocs/adaptacje-sezonowe/)** - Strategie dla polskiego klimatu
8. **[Protokoły awaryjne](https://tomyc.github.io/Meteopatia_MKDocs/protokoly-awaryjne/)** - Zarządzanie kryzysowe
9. **[Źródła literaturowe](https://tomyc.github.io/Meteopatia_MKDocs/zrodla-literaturowe/)** - 86 pozycji bibliograficznych

## 🎯 Kluczowe informacje

### Statystyki meteoropatii:
- **25-40%** populacji światowej doświadcza objawów meteoropatii
- **Kobiety 4x częściej** niż mężczyźni są wrażliwe na zmiany pogody
- **40-60%** redukcja objawów możliwa dzięki kompleksowym interwencjom stylu życia
- **6-10 hPa** to minimalna zmiana ciśnienia wywołująca objawy u wrażliwych osób

### Główne objawy:
- Bóle głowy i napięcie mięśniowe
- Trudności z koncentracją
- Lęk i niepokój
- Problemy z oddychaniem
- Wrażliwość na ból
- Zaburzenia snu

## 🛠️ Instalacja lokalna

### Wymagania:
- Python 3.7+
- pip

### Instalacja:

```bash
# Klonowanie repozytorium
git clone https://github.com/tomyc/Meteopatia_MKDocs.git
cd Meteopatia_MKDocs

# Instalacja MkDocs i tematu Material
pip install mkdocs mkdocs-material

# Uruchomienie serwera lokalnego
mkdocs serve
```

Portal będzie dostępny pod adresem: `http://localhost:8000`

### Budowanie statycznej wersji:

```bash
# Budowanie statycznej wersji
mkdocs build

# Pliki statyczne będą w katalogu site/
```

## 📁 Struktura projektu

```
Meteopatia_MKDocs/
├── docs/
│   ├── index.md                    # Strona główna
│   ├── meteoropatia.md            # Podstawy naukowe
│   ├── sposoby-leczenia.md        # Metody leczenia
│   ├── odzywienie.md              # Odżywianie przeciwzapalne
│   ├── cwiczenia.md               # Ćwiczenia fizyczne
│   ├── higiena-zycia.md           # Higiena życia
│   ├── narzedzia.md               # Narzędzia wspierające
│   ├── adaptacje-sezonowe.md      # Adaptacje sezonowe
│   ├── protokoly-awaryjne.md      # Protokoły awaryjne
│   └── zrodla-literaturowe.md     # Bibliografia
├── mkdocs.yml                     # Konfiguracja MkDocs
├── README.md                      # Ten plik
└── .github/
    └── workflows/
        └── ci.yml                 # GitHub Actions dla auto-deploy
```

## 🔧 Technologie

- **[MkDocs](https://www.mkdocs.org/)** - Generator statycznej dokumentacji
- **[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)** - Nowoczesny motyw Material Design
- **[GitHub Pages](https://pages.github.com/)** - Hosting statyczny
- **[GitHub Actions](https://github.com/features/actions)** - Automatyczne wdrożenie

## 📖 Podstawa naukowa

Portal opiera się na analizie **86 źródeł naukowych**, w tym:
- **56 artykułów** z recenzowanych czasopism naukowych
- **15 raportów** organizacji medycznych i zdrowotnych
- **8 przewodników** klinicznych i wytycznych
- **7 narzędzi** technologicznych i aplikacji

### Główne bazy danych:
- PubMed/PMC
- ScienceDirect
- Springer
- ResearchGate
- Google Scholar

## 🎨 Funkcjonalności

### Nawigacja:
- ✅ Responsywna nawigacja zakładkowa
- ✅ Rozwijalne sekcje
- ✅ Wyszukiwanie pełnotekstowe
- ✅ Powrót na górę strony

### Zawartość:
- ✅ Admonitions (informacje, ostrzeżenia, wskazówki)
- ✅ Podświetlanie składni kodu
- ✅ Automatyczny spis treści
- ✅ Linki krzyżowe między sekcjami

### Design:
- ✅ Material Design
- ✅ Ciemny/jasny motyw
- ✅ Optymalizacja mobilna
- ✅ Szybkie ładowanie

## 🏥 Zastrzeżenia medyczne

⚠️ **Ważne:** Ten przewodnik zawiera informacje oparte na najnowszych badaniach naukowych i może być wykorzystywany jako uzupełnienie, ale **nie zastępstwo profesjonalnej opieki medycznej**. W przypadku poważnych objawów zawsze skonsultuj się z lekarzem.

## 📜 Licencja

Ten projekt jest udostępniony na licencji MIT. Zobacz plik [LICENSE](LICENSE) dla szczegółów.

## 🤝 Współpraca

Projekt jest otwarty na współpracę i poprawki. Aby wnieść swój wkład:

1. Sforkuj repozytorium
2. Stwórz branch z funkcjonalnością (`git checkout -b feature/nowa-funkcja`)
3. Commituj zmiany (`git commit -am 'Dodaj nową funkcję'`)
4. Wypchnij na branch (`git push origin feature/nowa-funkcja`)
5. Otwórz Pull Request

## 📧 Kontakt

Jeśli masz pytania lub sugestie dotyczące portalu, możesz:
- Otworzyć [Issue](https://github.com/tomyc/Meteopatia_MKDocs/issues)
- Skontaktować się przez GitHub

## 🔄 Aktualizacje

Portal jest regularnie aktualizowany w oparciu o najnowsze badania naukowe. Sprawdzaj [Releases](https://github.com/tomyc/Meteopatia_MKDocs/releases) dla informacji o najnowszych zmianach.

## 📊 Statystyki

- **Liczba stron:** 10
- **Źródła naukowe:** 86 pozycji
- **Język:** Polski
- **Ostatnia aktualizacja:** 15 lipca 2025

---

**Meteoropatia - Kompleksowy Przewodnik** | Naukowe podejście do zarządzania wrażliwością meteorologiczną
