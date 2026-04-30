# Przegladarka Markdown SPA

Prosta aplikacja SPA (HTML + CSS + JS) do przegladania i edycji plikow Markdown.

## Funkcje

- drzewo plikow `.md` (rekurencyjnie z podkatalogow) ze zwijaniem i rozwijaniem folderow,
- edytor surowego Markdown,
- podglad na zywo,
- zapis przez przycisk `Zapisz` i skrot `Ctrl+S`,
- regulowana szerokosc paneli,
- zapamietywanie ostatniego pliku i stanu rozwinięcia drzewa (localStorage, per nazwa katalogu),
- brak funkcji tworzenia plikow/katalogow.

## Uruchomienie

1. Otworz `code.html` w aktualnym Chrome lub Edge.
2. Kliknij `Wybierz katalog` i wskaz katalog roboczy.
3. Wybierz plik `.md`, edytuj i zapisz.

## Uwagi techniczne

- Dostep do systemu plikow realizuje API `showDirectoryPicker` (wymaga wspieranej przegladarki).
- Podglad wykorzystuje `marked` + `DOMPurify` z CDN.
- Styl oparty o specyfikacje Neumorphism z pliku `Specyfikacja_Neumorphism.md`.

## Informacja o repozytorium

Historia repozytorium została uproszczona: zdalne repo zostało zastąpione jednym commitem zawierającym tylko `index.html`, `styles.css` oraz `README.md`.
Operacja wykonana lokalnie: pliki dodatkowe pozostały na dysku, ale nie są już śledzone przez Git. Data operacji: Thu Apr 30 2026.
