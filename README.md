# Portal Weryfikacji Podmiotów

Lekka aplikacja webowa (HTML, Tailwind CSS, JavaScript) umożliwiająca szybkie sprawdzanie podmiotów w wykazie podatników VAT (Biała Lista Ministerstwa Finansów) po numerze **NIP** lub **REGON** w motywie kolorystycznym inspirowanym logo Pepco.

## Funkcje
- **Wyszukiwanie po NIP i REGON** — walidacja formatu identyfikatora (10 cyfr dla NIP, 9 lub 14 cyfr dla REGON) oraz automatyczne formatowanie numeru NIP (`XXX-XXX-XX-XX`).
- **Karta podmiotu** — podgląd nazwy, statusu VAT, numerów rejestrowych (NIP, REGON, KRS), adresu oraz rachunków bankowych z białej listy w formacie `XX XXXX XXXX XXXX XXXX XXXX XXXX`.
- **Szybkie kopiowanie** — kopiowanie jednym kliknięciem numerów rejestrowych, adresu oraz numerów rachunków bankowych.
- **Historia wyszukiwań** — zapis ostatnich zapytań w `localStorage` z możliwością ponownego uruchomienia lub wyczyszczenia historii.
- **Obsługa błędów i awaryjny proxy** — czytelne komunikaty o błędach API/walidacji oraz zapasowe połączenie przez proxy w razie problemów z bezpośrednim dostępem.

## Uruchomienie
Otwórz plik `index.html` bezpośrednio w dowolnej przeglądarce internetowej.
