# CAS-INFE-21.12-Scripting-Project
Scripting Project - Group 10 test

## Kita Zürich
### Fragestellung
Welches Quartier in der Stadt Zürich ist am Besten geeinget, eine neue private Kita zu öffnen?

___Ansatz:___ Anhand von den verfügbaren Daten über Geburten, Einkommen, Kita-Belegungen in der Stadt Zürich soll man eine Entscheidung treffen. 

___Datensätze:___ wurden aus Open Data Zürich verwendet.
https://data.stadt-zuerich.ch/

Folgende drei Datensätze wurden für die Analyse benötigt:
1. Geburten nach Monat, Stadtquartier, Geschlecht und Herkunft  (1998 - 2021)
https://data.stadt-zuerich.ch/dataset/bev_monat_geburten_quartier_geschl_ag_herkunft_od4030/download/BEV403OD4030.csv

2. Kennzahlen zu Kitas (Kindertagesstätten) der Stadt Zürich nach Stadtquartier (2014 - 2020)
https://data.stadt-zuerich.ch/dataset/sd_zv_kitas_stadtquartier

3. Median-Einkommen steuerpflichtiger natürlicher Personen nach Jahr, Steuertarif und Stadtquartier (1999 - 2018)
https://data.stadt-zuerich.ch/dataset/fd_median_einkommen_quartier_od1003

### Umsetzung:
1. Daten laden
2. Daten bereinigen, aufbereiten und persistieren
3. Daten analysieren 
4. Daten visualisieren

### Tech Stack
Geabeitet wird mit JupyterLab und der Programmiersprache Python.
Daten sind im CSV Format vorhanden. 
