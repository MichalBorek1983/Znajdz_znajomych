# 🤝 Znajdź Znajomych

Aplikacja Streamlit, która na podstawie krótkiej ankiety przypisuje użytkownika do grupy podobnych osób (klastrowanie).

![Status](https://img.shields.io/badge/Status-Deployed-success)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red)

## Jak to działa

1. W panelu bocznym podajesz wiek, wykształcenie, ulubione zwierzęta, ulubione miejsce i płeć.
2. Model klastrowania PyCaret (`welcome_survey_clustering_pipeline_v2.pkl`), wytrenowany na danych z ankiety powitalnej (`welcome_survey_simple_v2.csv`), przypisuje Cię do jednej z grup.
3. Nazwy i opisy grup są w pliku `welcome_survey_cluster_names_and_descriptions_v2.json`. Przygotowano je w notebooku `Tworzymy nazwane klastry.ipynb` z użyciem modelu OpenAI.

Aplikacja ma trzy zakładki:

* **Analiza graficzna:** opis Twojej grupy, liczba osób i histogramy cech (wiek, wykształcenie, zwierzęta, miejsce, płeć).
* **Analiza statystyczna:** tabele liczności cech w każdej grupie.
* **Przegląd danych:** wykres sunburst z podziałem na grupy oraz opisy wszystkich grup.

## Uruchomienie

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Uwagi

* Aplikacja na Streamlit Community Cloud usypia się po okresie nieaktywności. Po wejściu wybierz "Yes, get this app back up".
* Fragment kodu z bazą wektorową Qdrant w `app.py` jest wyłączony (zakomentowany) i aplikacja go nie używa.

*Autor: Michał Borek*
