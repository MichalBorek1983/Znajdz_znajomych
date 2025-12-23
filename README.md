# 🤝 Znajdź Znajomych (Find Friends) – Aplikacja Streamlit

![Status](https://img.shields.io/badge/Status-Deployed-success)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red)

## 📄 O Projekcie
**Find Friends** to interaktywna aplikacja webowa, która pomaga użytkownikom znaleźć osoby o podobnych profilach lub zainteresowaniach w bazie danych.

Projekt ten jest przykładem zastosowania języka Python do budowy prostego systemu rekomendacyjnego (matching system) oraz prezentacji wyników w przyjaznym interfejsie graficznym.

### 🎯 Cel
Celem projektu było stworzenie narzędzia, które:
1.  Pobiera dane od użytkownika (np. poprzez formularz).
2.  Przeszukuje dostępny zbiór danych (dataset).
3.  Zwraca najlepiej dopasowane wyniki w czasie rzeczywistym.

---

## ⚙️ Funkcjonalności Aplikacji
* **Interaktywny Formularz:** Użytkownik może zdefiniować kryteria wyszukiwania (np. wiek, lokalizacja, zainteresowania) za pomocą suwaków i list rozwijanych.
* **Algorytm Dopasowania:** Aplikacja filtruje bazę danych i sortuje wyniki, aby znaleźć "najbliższych sąsiadów" lub osoby spełniające określone warunki.
* **Wizualizacja:** Prezentacja znalezionych profili w czytelnej formie (tabela lub karty).

---

## 🛠️ Stack Technologiczny

### Backend & Logic
* **Python:** Logika aplikacji.
* **Pandas:** Wczytywanie i filtrowanie danych (DataFrames).

### Frontend & Deployment
* **Streamlit:** Framework zamieniający skrypty Pythona w interaktywną stronę internetową.
* **Streamlit Community Cloud:** Platforma chmurowa, na której aplikacja została wdrożona i udostępniona publicznie.

---

## 🖥️ Jak uruchomić lokalnie?
Jeśli chcesz zobaczyć kod i uruchomić go na własnym komputerze:

1.  **Sklonuj repozytorium:**
    ```bash
    git clone [https://github.com/MichalBorek1983/Znajdz_znajomych.git](https://github.com/MichalBorek1983/Znajdz_znajomych.git)
    cd Znajdz_znajomych
    ```

2.  **Zainstaluj wymagane biblioteki:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Uruchom aplikację:**
    ```bash
    streamlit run app.py
    ```
---
*Autor: Michał Borek*
