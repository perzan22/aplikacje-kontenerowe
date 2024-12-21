# Volumes

Ćwiczenie pokazuje działanie volume, czyli woluminy, które zachowują dane między różnymi kontenerami.  

### Odpalenie serwera z kontenera i sprawdzenie, czy działa

![Zdjęcie 1](images/01.png)

### Zamiana plików kontenera plikiem z hosta i sprawdzenie działania

![Zdjęcie 2](images/02.png)

### Po zatrzymaniu kontenera odpalenie go na nowo nie ma naszej aktualizacji

![Zdjęcie 3](images/03.png)

### Wyświetlenie wszystkich volume

![Zdjęcie 4](images/04.png)

### Stworzenie nowego volume

![Zdjęcie 5](images/05.png)

### Usuwanie volume

![Zdjęcie 6](images/06.png)

### Stworzenie volume httpd_htdocs

![Zdjęcie 7](images/07.png)

### Uruchomienie kontenera i przekazanie mu volume

![Zdjęcie 8](images/08.png)

### Skopiowanie pliku html do kontenera z działającym volume

![Zdjęcie 9](images/09.png)

### Usunięcie i uruchomienie ponowne kontenera będzie zawierać naszą aktualizację dzięki użyciu volume

![Zdjęcie 10](images/10.png)

Volume pozwala przekazywać dane między jakiekolwiek kontenery httpd.  

### Zamiast używania volume, można też ustawić zmienną na ścieżkę hosta

![Zdjęcie 11](images/11.png)

### Teraz zmiana pliku index.html wpływa na działanie kontenera

![Zdjęcie 12](images/12.png)