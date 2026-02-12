# 🌍 Analiza Danych Przestrzennych w Pythonie

Repozytorium zawiera zestawy zadań wykonywanych w Pythonie podczas przedmiotu **"Analiza Danych Przestrzennych"**.  
Celem jest praktyczna nauka pracy z danymi przestrzennymi – wektorowymi, rastrowymi – oraz analiza procesów punktowych, autokorelacji i klasteryzacji danych.  

---

## 📂 Zawartość repozytorium

Zadania podzielone są według zestawów:

### 1️⃣-2️⃣ Dane wektorowe – `geopandas`
- 📌 Wczytywanie i przetwarzanie danych wektorowych  
- 📌 Operacje przestrzenne (spatial join, buffer, intersection)  
- 📌 Wizualizacja danych na mapach  

### 3️⃣ Dane rastrowe – `rasterio`
- 🌄 Wczytywanie i analiza danych rastrowych  
- 🌄 Operacje na rastrach (maskowanie, wycinanie, reindeksacja)  
- 🌄 Wizualizacja danych rastrowych  

### 4️⃣ Folium – interaktywna wizualizacja danych
- 🗺️ Tworzenie map interaktywnych  
- 🗺️ Dodawanie markerów, warstw i popupów  
- 🗺️ Wizualizacja danych przestrzennych w przeglądarce  

### 5️⃣ Pobieranie danych z OpenStreetMap – `overpass`
- 🌐 Tworzenie zapytań Overpass API  
- 🌐 Pobieranie i przetwarzanie danych OSM  

### 6️⃣ Generowanie procesów punktowych
- 🔹 Proces regularny z komponentem losowym  
- 🔹 Jednorodny proces Poissona  
- 🔹 Proces Materna  
- 🔹 Proces Thomasa  

### 7️⃣-9️⃣ Badanie intensywności procesów punktowych i relacji między punktami
- 📊 Szacowanie lokalne intensywności  
- 📊 Metoda funkcji jądrowej (KDE)  
- 📊 Funkcje G i F  
- 📊 Wykres Morishity  
- 📊 Testy statystyczne: chi-kwadrat, Kołmogorova-Smirnova 

### 🔟 Klasteryzacja i autokorelacja danych przestrzennych
- 🗂️ Metody klasteryzacji: k-means, hierarchiczna, DBSCAN, HDBSCAN  
- 🗂️ Macierze wag przestrzennych  
- 🗂️ Indeksy autokorelacji: Morana I i Geary’ego C  
