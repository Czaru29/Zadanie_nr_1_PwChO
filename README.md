# Zadanie_nr_1_PwChO

1. Stwórz plik Dockerfile za pomocą polecenia "touch Dockerfile" o następującej treści:

FROM nginx:alpine
COPY $HOME/folder/ /usr/share/nginx/html

2. Utwórz folder w katalogu home/student o nazwie "folder" i umieść w nim aplikację webową (można użyć aplikacji z repozytorium znajdującej się w folder.tar.gz)

3. Zbuduj obraz poleceniem: "docker build -t test ."

4. Uruchom kontener poleceniem: "docker run --name test -d -p 8080:80 test"

5. Aby uruchomić aplikację najpierw wprowadź polecenie: "docker port test" lub "docker ps -a" i odczytaj port na którym działa kontener a następnie wpisz ten adres do przeglądarki.
