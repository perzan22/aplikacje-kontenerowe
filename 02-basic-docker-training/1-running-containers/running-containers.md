# Running containers

Ćwiczenie pierwsze zawiera podstawowe komendy dotyczące uruchamiania kontenerów dockera.  

### Aktualnie zainstalowane obrazy na maszynie

![Zdjęcie 1](images/01.png)

### Wyszukanie dostępnych obrazów ubuntu

![Zdjęcie 2](images/02.png)

### Zainstalowanie obrazu ubuntu 22.04

![Zdjęcie 3](images/03.png)

### Zainstalowanie innej wersji tego samego obrazu

![Zdjęcie 4](images/04.png)

### Obrazy ubuntu są widoczne w systemie

![Zdjęcie 5](images/05.png)

### Usunięcie obrazu ubuntu 22.10

![Zdjęcie 6](images/06.png)

### Aktualnie ubuntu 22.10 nie jest zainstalowane na systemie

![Zdjęcie 7](images/07.png)

Skrótem do usuwania wszystkich obrazów jest ~docker rmi $(docker images -a -q)  

### Uruchomienie konteneru ubuntu, na którym odpalono komendę wyświetlającą napis 'Hello world!'

![Zdjęcie 9](images/09.png)

### Wyświetlenie wszystkich działających kontenerów

![Zdjęcie 10](images/10.png)

### Wyświetlenie wszystkich kontenerów, nawet tych zatrzymanych

![Zdjęcie 11](images/11.png)

### Uruchomienie komendy bash w obrazie ubuntu, jak widać nie można nic wpisać w terminal obrazu

![Zdjęcie 12](images/12.png)

### Po wpisaniu docker ps -a okazuje się, że kontener natychmiastowo się zatrzymał

![Zdjęcie 13](images/13.png)

### Uruchomienie kontenera w trybie interaktywnym

![Zdjęcie 14](images/14.png)

### Wykonanie komend w terminalu w obrazie ubuntu

![Zdjęcie 15](images/15.png)

### Uruchomienie kontenera w trybie detached (w tle)

![Zdjęcie 16](images/16.png)

### Komenda docker ps pokazuje teraz działający kontener

![Zdjęcie 17](images/17.png)

### Wywołanie komendy w działającym kontenerze

![Zdjęcie 18](images/18.png)

### Wypisanie wszystkich procesów w działającym kontenerze ubuntu

![Zdjęcie 19](images/19.png)

### Po wyjściu z terminala kontener dalej działa

![Zdjęcie 20](images/20.png)

### Zatrzymanie kontenera

![Zdjęcie 21](images/21.png)

### Docker pokazuje, że kontener został zatrzymany z kodem 137

![Zdjęcie 22](images/22.png)

### Usuwanie kontenera

![Zdjęcie 23](images/23.png)

Skrót do usuwania wszystkich kontenerów docker rm $(docker ps -a -q)

