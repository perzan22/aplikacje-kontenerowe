# DevOps with Docker part 2

Ćwiczenie wprowadza do zarządzania kontenerami za pomocą Docker Compose oraz wprowadza do sieci Dockera. 

## Zadanie 2.1

### Dockerfile

![Zdjęcie 1](images/01.png)

### docker-compose.yml

![Zdjęcie 2](images/02.png)

### Zapisane logi w pliku text.log

![Zdjęcie 3](images/03.png)

## Zadanie 2.2

### docker-compose.yml

![Zdjęcie 4](images/04.png)

### Wynik działania na stronie

![Zdjęcie 5](images/05.png)

## Zadanie 2.3

### Dockerfile backend

![Zdjęcie 6](images/06.png)

### Dockerfile frontend

![Zdjęcie 7](images/07.png)

### docker-compose.yml

![Zdjęcie 8](images/08.png)

### Działająca strona

![Zdjęcie 9](images/09.png)

## Zadanie 2.4

### docker-compose.yml z redisem pobranym z docker hub

![Zdjęcie 10](images/10.png)

### Działająca strona

![Zdjęcie 11](images/11.png)

## Zadanie 2.5

### docker-compose.yml zadania skalowania serwisów

![Zdjęcie 12](images/12.png)

### Użyta komenda do uruchomienia aplikacji

![Zdjęcie 13](images/13.png)

### Działające szybsze obliczanie wybiku

![Zdjęcie 14](images/14.png)

## Zadanie 2.6

### docker-compose.yml z dodaną bazą postgres

![Zdjęcie 15](images/15.png)

### Działające zapisywanie do bazy danych

![Zdjęcie 16](images/16.png)

## Zadanie 2.7

### Dodanie volume do docker-compose.yml

![Zdjęcie 17](images/17.png)

### Zapisanie odpowiedzi do bazy danych i zewnętrznego folderu database

![Zdjęcie 18](images/18.png)

### Zatrzymanie kontenerów

![Zdjęcie 19](images/19.png)

### Uruchomienie konteneró ponownie

![Zdjęcie 20](images/20.png)

### Wiadomości zostały odczytane po ponownym uruchomieniu

![Zdjęcie 21](images/21.png)

### Po usunięciu folderu database brak wiadomości w bazie danych

![Zdjęcie 22](images/22.png)

## Zadanie 2.8

### Dodanie serwera proxy

![Zdjęcie 23](images/23.png)

### Łączenie się za pomocą localhost do frontendu i localhost/api do backendu

![Zdjęcie 24](images/24.png)
![Zdjęcie 25](images/25.png)

## Zadanie 2.9

### Zmiana w docker-compose.yml w serwisie backend

![Zdjęcie 26](images/26.png)

### Zmiana w Dockerfile w serwisie frontend

![Zdjęcie 27](images/27.png)

Zmieniono też port w docker-compose.yml na - 5000 zamiast - 5000:5000.

### Plik nginx.conf

![Zdjęcie 28](images/28.png)

### Działająca strona

![Zdjęcie 29](images/29.png)

## Zadanie 2.10

### Wszystkie porty przestały być otwarte na zewnątrz - sprawdzenie

![Zdjęcie 30](images/30.png)

Ostatnie 4 porty są systemowymi portami, uruchomionymi przez usługę RPC, na Windows nie powinno się ich zamykać. Nie są one jednak wystawione na zewnątrz.


  