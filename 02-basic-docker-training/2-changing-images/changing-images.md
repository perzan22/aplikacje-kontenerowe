# Changing images

Ćwiczenie drugie zawiera komendy modyfikujące istniejące już obrazy.

### Pobranie obrazu ubuntu 16.04

![Zdjęcie 1](images/01.png)

### Utworzenie konteneru i uruchomienie terminalu, a następnie pingowanie adresu http

![Zdjęcie 2](images/02.png)

Ping nie działa, ponieważ obraz nie zainstalował automatycznie komendy. Należy ją zainstalować samemu.  

### Update software systemu ubuntu

![Zdjęcie 3](images/03.png)

### Instalacja pingu

![Zdjecie 4](images/04.png)

### Teraz można pingować

![Zdjęcie 5](images/05.png)

# Instalowanie zmian z kontenera do wszystkich obrazów ubuntu

### Sprawdzenie IP kontenera z zainstalowanym pingiem

![Zdjęcie 6](images/06.png)

### Docker commit - komenda bierze kontener i tworzy z niego obraz z wprowadzonymi zmianami

![Zdjęcie 7](images/07.png)

### Zaktualizowany obraz jest widoczny w systemie

![Zdjęcie 8](images/08.png)

### Uruchomienie nowego kontenera na obrazie z zainstalowanym już pingiem. Od razu można użyć komendy.

![Zdjęcie 9](images/09.png)