1.Tworzymy repozytorium na git (prawy gorny rog i plusik)
2. otwieramy katalog, w ktorym jest nasz projekt i otwieramy konsole "git bash"

3. Wykonujemy nastepujace komendy:

git init

git add . 
git commit -m "first commit"
git remote add origin https://github.com/mwolniak/test.git
git push -u origin master



4.

potem aby sprawdzac i/lub dodawac nowy kod do repozytorium posługujemy sie nastepujacymi komendami ;
git log (pokazuje historie naszych commitow)
git status (sprawdzamy czy dodalismy pliki do etapu, w ktorym mozemy je zcommitowac)
git add . (przygotowuje wszystkie pliki do wrzucenia w commit)
git commit -m "tresc commita" ( commitujemy plik)

git push (to powinno działać po ostatnim kroku w punkcie 3.)
ALBO
git push -u origin master 