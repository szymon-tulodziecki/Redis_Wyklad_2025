# Opis projektu

Repozytorium zawiera materiały do wykładu z podstaw korzystania z bazy danych Redis, przygotowane dla studentów I roku. Znajdziesz tu:

* prezentację PDF z teorią i praktycznymi zastosowaniami,
* zestawienie najważniejszych poleceń Redis (PDF),
* notebook Jupyter z przykładami kodu w Pythonie.

## Zawartość

| Plik | Opis |
|------|------|
| Wyklad_2025_Tulodziecki.pdf | Prezentacja: teoria, zastosowania, instalacja, polecenia, przykłady |
| Zestawienie-Polecen.pdf | Tabela: najważniejsze polecenia Redis dla wszystkich typów danych |
| Przyklady.ipynb | Notebook: praktyczne przykłady użycia Redis z Pythonem |

## W skrócie o Redis

* Redis to szybka, otwartoźródłowa baza danych typu klucz-wartość, działająca w pamięci RAM.
* Obsługuje różne typy danych: stringi, listy, hashe, zbiory, zbiory uporządkowane, strumienie i inne.
* Typowe zastosowania: cache, kolejki, przechowywanie sesji, szybkie operacje na danych.

## Jak korzystać z materiałów

* Teoria i przykłady – zacznij od prezentacji PDF.
* Szybka ściąga – sprawdź Zestawienie-Polecen.pdf (polecenia Redis dla każdego typu danych).
* Kod w Pythonie – uruchom notebook Przyklady.ipynb i testuj polecenia na lokalnej lub chmurowej instancji Redis.

## Szybki start z Redis + Python

### Instalacja klienta Redis dla Pythona
```
# Instalacja klienta Redis dla Pythona
pip install redis
```
```
import redis
r = redis.Redis(host='localhost', port=6379, db=0)
r.set('klucz', 'wartosc')
print(r.get('klucz').decode())
```
### Instalacja klienta Redis dla Pythona
1. Zainstaluj Redis lokalnie lub użyj Redis Cloud (instrukcja w prezentacji).

2. Otwórz Przyklady.ipynb w Jupyter Notebook lub VS Code.

3. Wykonuj kolejne komórki, obserwuj efekty i modyfikuj kod.
