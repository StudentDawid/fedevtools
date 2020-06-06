## Zadania GIT

1. Jeżeli nie masz, załóż konto na www.github.com
2. Stwórz nowe prywatne repozytorium o dowolnej nazwie wraz z plikiem README.md. WAŻNE - musi byc plik README.md.
3. Przejdź do repozytorium na stronie githuba. Zbadaj stronę.
4. Sklonuj repozytorium do siebie lokalnie, uzywając `git clone` i przejdź w konsoli do tego repozytorium.
5. Sprawdź stan repozytorium komendą `git status`
6. Jeżeli nie istnieje, stwórze plik README.md.
7. Zmień plik README.md. Sprawdź stan repozytorium komendą `git status`
8. Zacommituj zmiany, używając `git commit -m ""`. Sprawdź stan repozytorium komendą `git status`
9. Wyślij zmiany na serwer, uzywając `git push`. Sprawdź stan repozytorium komendą `git status`
10. Na stronie githuba zmień plik README.md i zacommituj zmiany. Sprawdź stan repozytorium komendą `git status`
11. W repozytorium pobierz zmiany, używając `git pull`. Sprawdź stan repozytorium komendą `git status`
12. Stwórz 3 pliki, a.txt, b.txt oraz c.txt i wypełnij je dowolną treścią. Dodaj je wszystkie do obserwowanych komendą `git add`
13. Zacommituj plik b oraz c, po czym edytuj plik c. Sprawdź stan repozytorium komendą `git status`
14. Wypuszuj zmianny. Sprawdź stan repozytorium komendą `git status`.
15. Dodaj wszystkie pliki do obserwowanych, zacommituj je i wypchnij do repozytorium. Sprawdź stan repozytorium komendą `git status`

## Przydatne komendy

1. Klonowanie repozytorium - git clone <LINK-DO-REPO> np. git clone https://github.com/StudentDawid/fedevtools.git
2. Tworzenie brancha - `git branch <NAZWA_BRANCHA>` np. `git branch nowyBranch`
3. Zmiana brancha - `git checkout <NAZWA_BRANCHA` np. `git checkout nowyBranch`
4. Dodanie pliku do obserwowania - `git add <NAZWA_PLIKU>`
5. Commitowanie zmian - `git commit -m ""`
6. Wypychanie zmian do repozytorium zdalnego - `git push <NAZWA_BRANCHA>` np. `git push origin master` lub `git push`
7. Pobieranie zmian z repozytirum zdalnego - `git pull`
8. Ustawianie configu:
   1. `git config --global user.name “Imie Nazwisko”`
   2. `git config --global user.email testowy@email.pl`
9. Czytanie configu:
   1. `git config --get user.name`
   2. `git config --get user.email`

## Przydatne linki

1. Oficjalna strona GITa - https://git-scm.com/
2. Podstawy gita - https://git-scm.com/book/pl/v1/Podstawy-Gita-Pierwsze-repozytorium-Gita
3. git-flow - https://danielkummer.github.io/git-flow-cheatsheet/index.pl_PL.html
4. Github - https://github.com/
5. GitFork - https://git-fork.com/
6. Prezentacja z GITa - https://docs.google.com/presentation/d/19vuLLYHbpkQoT7LaiIZuQgPY89YXavuQKHck6M19JNQ/edit?usp=sharing
