# Skrzynki 1.1.0 — źródła

Projekt Maven dla Paper 1.21.4 / Java 21. Otwórz folder w IntelliJ IDEA lub wrzuć cały projekt do repozytorium GitHub.

## Komendy
- `/stworzskrzynie <nazwa> <kolor>` — tworzy skrzynię. Kolory: `0-9` albo `a-f` (np. `/stworzskrzynie legendarna e`).
- `/skrzynia-edit <nazwa>` — otwiera edytor nagród; klik zwiększa wagę/szansę, Shift+klik zmniejsza.
- `/skrzynia-ustawlokalizacje <nazwa>` — następnie kliknij blok, który ma otwierać menu skrzyni.
- `/otworzskrzynie <nazwa>` — otwiera menu skrzyni.
- `/skrzynka przeladuj` — przeładowuje konfigurację.

## Budowanie
Wymaga JDK 21 i Maven. Uruchom `mvn package`; plik wynikowy pojawi się w `target/Skrzynki-1.1.0.jar`.

## Uwaga
To odtworzony projekt źródłowy na podstawie dostarczonego pliku JAR, a nie oryginalne źródła autora. Przed podmianą na serwerze przetestuj na kopii świata. Menu podglądu i edytor nagród są zaimplementowane; mechanika wydawania nagród po użyciu klucza wymaga dalszego dopasowania do docelowego systemu kluczy.
