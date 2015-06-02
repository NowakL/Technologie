# Moje notatki z pracy na githabie przez Ubuntu

### Podczas pracy wykorzystuję wiersz poleceń i zwracam uwagę na składnię, która musi być super dokładna.

1. **Instalacja oprogramowania github na Linuxie i przygotowanie do pracy**:

 + sudo apt-get install git - *instalacja github na Linuxie*
 + git config --global user.name "lsnarski" - *wprowadzam mój login*
 + git config --global user.email "lsnarski@o2.pl" - *wprowadzam mój email*

2. **Rozpoczęcie pracy**

 + mkdir gittest - *tworzę folder (repozytorium), które będzie tożsame z repozytorium na githubie*
 + cd gittest - *wchodzę w ten folder (repozytorium)*
 + echo "# gittest" >> README.md - *tworzę plik*
 + git init - *startuję gita w tym folderze*
 + git add README.md - *dodaję plik do śledzenia*
 + git commit -m "first commit" - *wprowadzam zmiany*
 + git remote add origin https://github.com/lsnarski/gittest.git - *łączę z repozytorium na githubie*
 + git push -u origin master - *przesyłam zmiany na github*

3. **Ważne komendy**

 + git clone https://github.com/lsnarski/lsnarski.github.io.git - *klonujesz całe reozytorium do siebie do folderu na dysku*
 + git status - *sprawdzasz, które repozytorium jest śledzone, zmienione itp*
 + git add - *dodajesz plik do śledzenia*
 + git rm - *usuwasz plik ze śledzenia*
 + git commit -m -a - *wprowadzasz zmiany w plikach*


## Pamiętaj, to są tylko podstawowe polecenia, których jest znacznie więcej

