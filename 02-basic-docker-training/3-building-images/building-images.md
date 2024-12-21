# Building images

W trzecim ćwiczeniu pokazane zostanie budowanie nowych obrazów za pomocą Dockerfile.  

### Usunięcie obrazu ubuntu z pingiem

![Zdjęcie 1](images/01.png)

## Tworzenie dockerfile

### Zdefiniowanie obrazu

![Zdjęcie 2](images/02.png)

### Komendy instalujące ping w obrazie

![Zdjęcie 3](images/03.png)

### Cały dockerfile

![Zdjęcie 4](images/04.png)

### Budowanie obrazu z Dockerfile

![Zdjęcie 5](images/05.png)

### Powtórzenie tej samej komendy pobierze obraz z pamięci podręcznej cache

![Zdjęcie 6](images/06.png)

### Docker images pokazuje zbudowany obraz (167MB)

![Zdjęcie 7](images/07.png)

### Optymalizacja obrazu edytując Dockerfile komendą czyszczącą logi instalacji

![Zdjęcie 8](images/08.png)

### Obraz jest teraz mniejszy 139MB

![Zdjęcie 9](images/09.png)

### Dodanie zmiennej środowiskowej ENV oraz komendę CMD, która wykonuje operacje po uruchomieniu obrazu

![Zdjęcie 10](images/10.png)

### Uruchomienie obrazu wywoła automatycznie ping

![Zdjęcie 11](images/11.png)