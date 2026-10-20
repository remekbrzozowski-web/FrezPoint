# FrezPoint

## Status projektu

To repozytorium nie zawiera jeszcze plików gotowej witryny. Obecnie dostępne są dokumentacja projektu oraz konfiguracja publikacji Netlify. Oryginalny pakiet strony nie został odnaleziony w dostępnej historii repozytorium, jego gałęziach ani w bieżącym workspace. Nie oznacza to, że archiwum ZIP zostało utracone.

Docelowy projekt opisany wcześniej obejmuje statyczną witrynę z 11 podstronami, logo 07, ciemnoczerwoną kolorystyką, galerią realizacji oraz naciskiem na projektowanie CAD. README z poprzedniej wersji wspomina też o danych kontaktowych dla Radwanic, formularzu przygotowującym plik zapytania (bez wysyłania danych), poglądowych zdjęciach i pakiecie WordPress.

## Publikacja przez Netlify

Plik `netlify.toml` przygotowuje wdrożenie statycznej witryny z katalogu głównego repozytorium, bez procesu kompilacji. Konfiguracja nie zastępuje brakujących plików witryny. Przed publikacją trzeba przywrócić właściwy pakiet strony i sprawdzić, czy zawiera `index.html`.

Szczegółowa lista brakujących materiałów znajduje się w [DEPLOYMENT.md](DEPLOYMENT.md).

## Pakiet WordPress

Wcześniejszy opis wskazywał pakiet `downloads/FrezPoint-WordPress.zip`, ale ten plik nie znajduje się obecnie w repozytorium. Motyw WordPress nie działa na statycznym hostingu Netlify; do wdrożenia na Netlify potrzebne są pliki wersji statycznej.
