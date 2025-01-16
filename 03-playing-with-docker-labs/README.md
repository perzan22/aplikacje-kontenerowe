# Playing with docker labs

Play with docker labs jest narzędziem uczącym Dockera w praktyce. Narzędzie zawiera wbudowaną konsolę na której wykonuje się zadania.  
Narzędzie uczy dockera od podstaw do bardziej zaawansowanych funkcji. Podzielony jest na część dla developerów i DevOps. Poniżej zadania będą dla developerów.  
Na każdym zdjęciu widoczny jest indeks studenta.

---

## Docker for Beginners - Linux

Moduł pokazuje podstawy dockera.

### Sklonowanie środowiska GitHub

![Zdjęcie 1](images/01.png)

### Uruchomienie kontenera alpine - hostname wyświetla ID kontenera

![Zdjęcie 2](images/02.png)

### Wylistowanie wszystkich kontenerów

![Zdjęcie 3](images/03.png)

### Uruchomienie interaktywnego kontenera ubuntu

![Zdjęcie 4](images/04.png)

### Uruchomienie różnych komend w terkminalu ubuntu: ls - wylistowanie zawartości plików, ps - pokazuje działające procesy, cat - wyświetla wersję ubuntu, flaga rm usuwa kontener po zatrzymaniu

![Zdjęcie 5](images/05.png)

### Uruchomienie kontenera mysql w tle: --detach - uruchamia w tle, --name - nazywa kontener, -e ustawia zmienną środowiskową

![Zdjęcie 6](images/06.png)\

### Wylistowanie działających kontenerów - bez paramteru all

![Zdjęcie 7](images/07.png)

### Wypisanie logów kontenera

![Zdjęcie 8](images/08.png)

### Wypisanie procesów działających w kontenerze

![Zdjęcie 9](images/09.png)

### Używanie komendy exec, do wykonania komend w działającym kontenerze - wypisanie wersji MySQL, uruchomienie nowego terminala, wypisanie wersji z terminala

![Zdjęcie 10](images/10.png)

---

## Tworzenie Dockerfile i uruchamianie aplikacji z Dockerfile

### Wyświetlenie zawartości Dockerfile

![Zdjęcie 11](images/11.png)

### Zapisanie lokalnie swojego DockerID

![Zdjęcie 12](images/12.png)

### Stworzenie nowego obrazu używając Dockerfile, tagując swoim DockerID

![Zdjęcie 13](images/13.png)

### Uruchomienie kontenera z własną aplikacją

![Zdjęcie 14](images/14.png)

### Działająca strona

![Zdjęcie 15](images/15.png)

### Usunięcie kontenera po zakończeniu działania

![Zdjecie 16](images/16.png)

---

## Modyfikowanie własnej aplikacji w kontenerze

### Uruchomienie kontenera w docelowym folderze za pomocą --mount

![Zdjęcie 17](images/17.png)

### Edycja index.html

![Zdjęcie 18](images/18.png)

### Nowy widok strony

![Zdjęcie 19](images/19.png)

### Zmiana odbyła się w kontenerze, a nie zmieniono obrazu, więc po usunięciu i odpaleniu kontenera na nowo

![Zdjęcie 20](images/20.png)

### Strona wraca do oryginału

![Zdjęcie 21](images/21.png)

### Budowanie nowego obrazu i nadanie mu tagu 2.0

![Zdjęcie 22](images/22.png)

### Uruchomienie kontenera z obrazu 2.0

![Zdjęcie 23](images/23.png)

### Widok strony 2.0

![Zdjęcie 24](images/24.png)

### Uruchomienie starej wersji na innym porcie

![Zdjęcie 25](images/25.png)

### Widok strony na porcie 8080

![Zdjecie 26](images/26.png)

### Wylistowanie obrazów dostępnych lokalnie

![Zdjęcie 27](images/27.png)

### Zalogowanie się i wysłanie obrazów 1.0 i 2.0 na DockerHUB

![Zdjecie 28](images/28.png)

### Obrazy sa widoczne na DockerHUB

![Zdjęcie 29](images/29.png)

---

## Application Containerization and Microservice Orchestration

Moduł pokazuje działanie Docker Compose, a więc konteneryzacja różnych komponentów aplikacji jako mikroserwisy i następne zarządzanie nimi przez mechanizm orchestration.

## Skrypt linkextractor.py

### Zawartość skryptu

![Zdjęcie 30](images/30.png)

### Próby uruchomienia skryptu zakończone niepowodzeniem, przez na przykład brak biblioteki requests

![Zdjęcie 31](images/31.png)

W takich przypadkach konteneryzacja się najbardziej przydaje.

## Konteneryzacja skryptu

### Zawartość Dockerfile

![Zdjęcie 32](images/32.png)

### Budowanie obrazu za pomocą Dockerfile (jak widać będzie posiadać biblioteki requests i beautifulsoup4)

![Zdjęcie 33](images/33.png)

### Uruchomienie kontenera zapewnia poprawne działanie skryptu - wypisuje linki ze stron

![Zdjęcie 34](images/34.png)

## Ulepszenie skonteneryzowanego skryptu

### Zbudowanie obrazu ulepszonego skryptu

![Zdjęcie 35](images/35.png)

### Ulepszony output skryptu

![Zdjęcie 36](images/36.png)

## Konteneryzacja serwisu API

### Następna wersja skryptu używana jest w pliku python

![Zdjęcie 37](images/37.png)

### Zbudowanie, uruchomienie i wylistowanie skryptu

![Zdjęcie 38](images/38.png)

### Wysłanie zapytania HTTP pobiera linki ze strony

![Zdjęcie 39](images/39.png)

## Webowa wersja skryptu

### Zawartość docker-compose następnej wersji skryptu - jak widać łączy dwa obrazy: linkextractor i php 

![Zdjęcie 40](images/40.png)

### Uruchomienie serwisów z docker-compose, wylistowanie pokazuje dwa działające kontenery

![Zdjęcie 41](images/41.png)

### Link Extractor działa w wersji webowej

![Zdjęcie 42](images/42.png)

### Zamiana wszystkich powtórzeń Link Extractor na Super Link Extractor

![Zdjęcie 43](images/43.png)

### Wygląd zaktualizowanej strony

![Zdjęcie 44](images/44.png)

### Zatrzymanie i usuwanie serwisów z docker-compose

![Zdjęcie 45](images/45.png)

## Konteneryzacja z użyciem bazy danych Redis, która używa cache

### Dockerfile

![Zdjęcie 46](images/46.png)

### main.py

![Zdjęcie 47](images/47.png)

### docker-compose zawiera obraz python, php i redis

![Zdjęcie 48](images/48.png)

### Po zbudowaniu docker-compose, działa strona webowa, każde kolejne wyodrębnienie linków działa szybciej dzięki cache z redisa

![Zdjęcie 49](images/49.png)

### Odpalenie konsoli Redis wypisuje wyniki

![Zdjęcie 50](images/50.png)

## Zmiana API python na Ruby

### Aplikacja podobna jednak API zmienione z python na Ruby

![Zdjecie 51](images/51.png)

### Aplikacja webowa działa

![Zdjęcie 52](images/52.png)

---

## Docker swarm

Moduł pokazuje działanie działanie Docker swarm.

## Aplikacja do głosowania

### Zainicjowanie środowiska Docker swarm, działanie w terminalu swarm manager

![Zdjęcie 53](images/53.png)

### Dodanie węzła worker do środowiska swarm

![Zdjęcie 59](images/59.png)

### Wypisanie listy węzłów w środowisku swarm

![Zdjęcie 54](images/54.png)

### Pobranie z github kodu aplikacji

![Zdjęcie 55](images/55.png)

### Wdrożenie aplikacji z pliku docker-compose do stosu swarma

![Zdjęcie 56](images/56.png)

### Wypisanie ile serwisów znajduje się na stosie swarma

![Zdjęcie 57](images/57.png)

### Wypisanie serwisów działających na stosie swarm

![Zdjęcie 58](images/58.png)

### Wypisanie zadań serwisu vote

![Zdjęcie 60](images/60.png)

