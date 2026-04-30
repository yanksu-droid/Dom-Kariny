# Dom Kariny - publikacja na GitHub Pages

Ten folder jest gotowy do wrzucenia na GitHub Pages.

## Pliki do wysłania

- `index.html`
- `.nojekyll` opcjonalnie, ale warto dodać

## Uwaga o prywatności

Darmowe GitHub Pages działa najprościej z publicznym repozytorium. To oznacza, że plik `index.html` będzie publicznie widoczny. Dane wpisywane później w aplikacji zapisują się lokalnie w przeglądarce użytkownika, ale dane startowe zaszyte w pliku są widoczne w kodzie strony.

## Najprostsza ścieżka

1. Wejdź na https://github.com i załóż konto albo zaloguj się.
2. Kliknij `+` w prawym górnym rogu.
3. Wybierz `New repository`.
4. Nazwij repozytorium, np. `dom-kariny`.
5. Ustaw `Public`.
6. Kliknij `Create repository`.
7. W nowym repozytorium kliknij `uploading an existing file` albo `Add file` -> `Upload files`.
8. Przeciągnij plik `index.html` z tego folderu.
9. Kliknij `Commit changes`.
10. Wejdź w `Settings` -> `Pages`.
11. W sekcji `Build and deployment` ustaw:
    - `Source`: `Deploy from a branch`
    - `Branch`: `main`
    - folder: `/ (root)`
12. Kliknij `Save`.
13. Po 1-3 minutach GitHub pokaże adres strony, zwykle:
    `https://TWOJ_LOGIN.github.io/dom-kariny/`

## Aktualizacja aplikacji później

Jeśli zmienisz aplikację lokalnie, ponownie wrzuć nowy `index.html` do repozytorium i kliknij `Commit changes`. GitHub Pages sam odświeży stronę po chwili.
