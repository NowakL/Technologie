# Moje otatki z pracy na githabie przez Ubuntu

### Podczas pracy wykorzystuję wiersz poleceń i zwracam uwagę na składnię, która musi być super dokładna.

1. **Instalacja oprogramowania github na Linuxie i przygotowanie do pracy**:

 + sudo apt-get install git - *instalacja github na Linuxie*
 + git config --global user.name "lsnarski" - *wprowadzam mój login*
 + git config --global user.email "lsnarski@o2.pl" - *wprowadzam mój email*

2. **Rozpoczęcie pracy**

 + mkdir gittest - *tworzę folder (repozytorium), które będzie tożsame z repozytorium na githubie*
 + cd gittest - *wchodzę w ten folder (repozytorium)*
 + 

echo "# gittest" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/lsnarski/gittest.git
git push -u origin master

git clone https://github.com/lsnarski/lsnarski.github.io.git


sudo apt-get install npm

$ cd your_repo_root/repo_name
$ git fetch origin
$ git checkout gh-pages

git status
git add
git rm

git commit -m -a
