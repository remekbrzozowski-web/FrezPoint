# Przygotowanie publikacji FrezPoint

## Stan sprawdzony 20 października 2026 r.

Gałąź `main` zawierała wyłącznie `README.md`. Repozytorium ma tylko gałąź `main` i jeden commit inicjalizacyjny z 9 października 2026 r. W bieżącym workspace nie znaleziono plików projektu.

Próba pobrania `index.html` oraz `downloads/FrezPoint-WordPress.zip` z repozytorium zwróciła 404. Nie odnaleziono też kopii repozytorium o nazwie FrezPoint w dostępnych repozytoriach GitHub. To ustala, czego nie ma w sprawdzonych źródłach; nie potwierdza utraty oryginalnego archiwum.

## Materiały potrzebne do publikacji

Należy odnaleźć lub ponownie udostępnić oryginalny pakiet statycznej witryny, w tym:

- plik wejściowy `index.html`;
- pozostałe 10 podstron (ich nazwy i ścieżki nie są opisane w obecnym repozytorium);
- arkusze stylów, skrypty i inne pliki używane przez witrynę;
- logo 07 oraz zasoby graficzne, w szczególności obrazy galerii;
- pliki i logikę formularza zgodne z opisanym zachowaniem: przygotowanie pliku zapytania bez wysyłania danych.

Nie rekonstruuj tych plików na podstawie samego README. Po odzyskaniu pakietu zachowaj jego istniejącą strukturę i zweryfikuj lokalne odnośniki oraz ścieżkę strony głównej.

Pakiet WordPress wspomniany w poprzednim README, `downloads/FrezPoint-WordPress.zip`, również nie jest obecnie dostępny. Jest osobnym materiałem i nie jest wymagany do wdrożenia wersji statycznej na Netlify.

## Ustawienia Netlify

- Katalog publikacji: `.` (katalog główny repozytorium)
- Komenda budowania: pusta, bez procesu kompilacji
- Wymagany plik w katalogu publikacji: `index.html`

Te ustawienia znajdują się w `netlify.toml`. Po dodaniu oryginalnych plików statycznych repozytorium będzie miało konfigurację publikacji, ale wdrożenie nie powinno być traktowane jako gotowe przed przywróceniem i weryfikacją witryny.
