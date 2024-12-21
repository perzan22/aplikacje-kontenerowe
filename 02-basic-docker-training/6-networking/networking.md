# Networking

Ostatnie ćwiczenie pokazuje działanie sieci i połączeń między kontenerami

### Wyświetlenie wszystkich dostępnych sieci

![Zdjęcie 1](images/01.png)

### Nowe kontenery domyślnie są w sieci bridge, sieć można sprawdzić

![Zdjęcie 2](images/02.png)

### Uruchomienie dwóch kontenerów pingujących

![Zdjęcie 3](images/03.png)

Jak widać kontener pinger poprawnie pinguje pierwszy z kontenerów. Adres może się jednak zmienić, dlatego lepiej pingować po nazwie kontenera.

### Zmiana PING_TARTGET na nazwę kontenera

![Zdjęcie 4](images/04.png)

Nie da się w sieci bridge pingować po nazwie, kontener od razu po uruchomieniu wyrzucił błąd i zatrzymał swoje działanie.

### Tworzenie własnej sieci

![Zdjęcie 5](images/05.png)

### Dodanie dwóch kontenerów do własnej sieci

![Zdjęcie 6](images/06.png)

Pinger może w stworzonej sieci pingować po nazwie kontenera

### Uruchomienie dwóch kontenerów baz danych postgress w sieci skynet

![Zdjęcie 7](images/07.png)

Niestety bazy danych po uruchomieniu od raazu się wyłączają. Załóżenuiem zadania było to, że w jednej sieci te bazy mogą się ze sobą połączyć po tym samym porcie lub łączą się z hostem.


