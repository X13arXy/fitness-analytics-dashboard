# 🏋️ Fitness Analytics Dashboard (Excel & VBA)

Profesjonalne narzędzie analityczne typu **ETL (Extract-Transform-Load)**, które automatyzuje monitorowanie postępów treningowych. Projekt zamienia surowe dane w interaktywny dashboard zarządczy.

![Podgląd Dashboardu](dashboard.png)


## 🚀 Główne Funkcje

* **Automatyzacja ETL (VBA):** Skrypt `LogikaETL.bas` automatycznie pobiera dane z formularza, czyści je i archiwizuje w bazie historycznej.
* **Analityka Biznesowa:** Obliczanie wskaźników KPI:
    * **WoW Growth:** Wzrost objętości tydzień do tygodnia.
    * **Benchmarking:** Porównanie wyników z historycznymi okresami.
* **UI/UX Design:** Nowoczesny interfejs w trybie **Dark Mode** z zablokowanym obszarem roboczym (ScrollArea) dla lepszego doświadczenia użytkownika.
* **Data Integrity:** Zabezpieczenia przed błędnym wprowadzaniem danych (Data Validation).

## 🛠️ Technologie

* **Microsoft Excel 365**
* **VBA (Visual Basic for Applications)**
* **SQL Logic** (zastosowana w formułach `SUMIFS` / `FILTER`)
* **Data Visualization**

## 💻 Jak uruchomić?

1.  Pobierz plik `Fitness_Dashboard.xlsm`.
2.  Przy otwarciu kliknij **"Włącz zawartość" (Enable Content)**, aby aktywować makra.
3.  Rozpocznij wprowadzanie danych w zakładce "Trening A".
