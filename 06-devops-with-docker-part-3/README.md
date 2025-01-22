# DevOps with Docker part 3

Ćwiczenia z powyższego folderu wprowadzają do optymalizacji kontenerów oraz o wdrażaniu. Zostaną również poruszone inne rozwiązania zarządzania kontenerów.

## Zadanie 3.1

### Plik deploy

![Zdjęcie 1](images/01.png)

### Działanie GitHub Actions

![Zdjęcie 2](images/02.png)

### Odpalenie kontenera z utworzonego obrazu w tle

![Zdjęcie 3](images/03.png)

### Działająca strona na porcie 8080

![Zdjęcie 4](images/04.png)

### Watchtower

![Zdjęcie 5](images/05.png)

### Uruchomienie watchtower i kontenera w tle

![Zdjęcie 6](images/06.png)

### Strona przed zmianami

![Zdjęcie 9](images/09.png)

### Wprowadzenie zmian w kodzie i push na github

![Zdjęcie 7](images/07.png)

### Zmiana po włączeniu watchtower wywołała GitHub Actions, więc image powinien się automatycznie zaktualizować

![Zdjęcie 8](images/08.png)

### Image w Docker Hub się zaktualizował

![Zdjęcie 10](images/10.png)

### Zmiana na stronie po odświeżniu strony, bez uruchmiania kontenera na nowo

![Zdjęcie 11](images/11.png)

## Zadanie 3.3

### Skrypt builder.sh

![Zdjęcie 12](images/12.png)

### Uruchomienie skryptu

![Zdjęcie 13](images/13.png)
![Zdjęcie 14](images/14.png)

### Nowy obraz w Docker Hub

![Zdjęcie 15](images/15.png)

## Zadanie 3.4

### Dockerfile

![Zdjęcie 16](images/16.png)

### Dodanie logowania do skryptu

![Zdjęcie 17](images/17.png)

### Zbudowanie obrazu z Dockerfile

![Zdjęcie 18](images/18.png)

### Uruchomienie kontenera Docker

Brak zdjęcia przez dane logowania

### Utworzony obraz test

![Zdjęcie 19](images/19.png)

## Zadanie 3.5

### Dockerfile frontend z dodanym userem

![Zdjęcie 20](images/20.png)

### Dockerfile backend z dodanym userem

![Zdjęcie 21](images/21.png)

### Sprawdzenie usera frontend

![Zdjęcie 22](images/22.png)

### Sprawdzenie usera backend

![Zdjęcie 23](images/23.png)

### Sprawdzenie działania strony

![Zdjęcie 24](images/24.png)

## Zadanie 3.6

### Sprawdzenie wielkości obrazów przed zmianami

![Zdjęcie 25](images/25.png)

### Połączenie komend RUN w Dockerfiles i usunięcie niepotrzebnych zależności po produkcji

![Zdjęcie 26](images/26.png)
![Zdjęcie 27](images/27.png)

### Modyfikacje w Dockerfiles zmniejszyły frontend i backend o kolejno 170MB i 90MB

![Zdjęcie 28](images/28.png)

## Zadanie 3.7

### Zmiana image w Dockerfiles na node:16-alpine i golang:1.16-alpine spwoodowała zmniejszenie obrazów o 500-600MB

![Zdjęcie 29](images/29.png)

### Aplikacja nadal działa

![Zdjęcie 30](images/30.png)

## Zadanie 3.8

### Multi-stage Dockerfile frontend

![Zdjęcie 31](images/31.png)

### Rozmiar frontend image mniejszy o kolejne 170MB

![Zdjęcie 32](images/32.png)

## Zadanie 3.9

### Multi-stage Dockerfile backend

![Zdjęcie 33](images/33.png)

### Rozmiar backend image zmniejszony do 25MB

![Zdjęcie 34](images/34.png)

## Zadanie 3.10

### Początkowy rozmiar obrazu perzan22/express_app

![Zdjęcie 35](images/35.png)

### Dockerfile przed zmianami

![Zdjęcie 36](images/36.png)

### Zaktualizowany Dockerfile

![Zdjęcie 37](images/37.png)

### Rozmiar obrazu po aktualizacji mniejszy o 800MB

![Zdjęcie 38](images/38.png)

### Kontener używa safeUser

![Zdjęcie 39](images/39.png)

### Aplikacja działa

![Zdjęcie 40](images/40.png)

## Zadanie 3.11

### Diagram kubernetess

![Zdjęcie 41](images/41.png)









