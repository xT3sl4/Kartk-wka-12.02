# Kartkowka-12.02
## Instrukcje Ogólne
- Utwórz fork repozytorium testowego
- Wszystkie commity powinny przestrzegać konwencji: `ZADANIE-<numer>: <opis zmian>`
- Każde zadanie powinno być wykonane na osobnym branchu
- Dokumentuj swoje polecenia w pliku commands.md dla każdego zadania

## Zadania

### Zadanie 1: Zarządzanie Branchami (15 punktów)
1. Utwórz nowy branch `feature/zad1/<twój-numer-indeksu>`
2. Stwórz plik `student.md` zawierający:
   - Nagłówek z Twoim numerem indeksu
   - Listę 3 ulubionych technologii
   - Jedno zdanie pogrubione
3. Wykonaj minimum 2 osobne commity ze znaczącymi zmianami
4. Wypchnij branch na zdalne repozytorium

### Zadanie 2: Rebase i Rozwiązywanie Konfliktów (15 punktów)
1. Utwórz nowy branch `feature/zad2/<twój-numer-indeksu>` z maina
2. Dodaj plik `profile.md` z następującą zawartością:
   - Nagłówek pierwszego poziomu z Twoim numerem indeksu
   - Podtytuł z Twoim ulubionym językiem programowania
   - Krótki kod w bloku kodu z przykładem w tym języku
3. W międzyczasie prowadzący doda inne treści do tego samego pliku na mainie
4. Wykonaj rebase swojego brancha na main
5. Rozwiąż powstałe konflikty
6. Wykonaj bezpieczny force push zmian

### Zadanie 3: Pull Request i Cherry-pick (10 punktów)
1. Stwórz Pull Request dla brancha z Zadania 2
2. W opisie PR zawrzyj:
   - Tytuł według formatu "Zadanie 2: <twój-numer-indeksu> - Rozwiązanie konfliktów"
   - Opis wprowadzonych zmian w formacie Markdown, zawierający:
     * Listę wprowadzonych zmian
     * Jedno pogrubione zdanie opisujące cel zmian
3. Wykonaj cherry-pick ostatniego commita z maina do nowego brancha `feature/zad3/<twój-numer-indeksu>`

## Kryteria Oceny
- Poprawne nazewnictwo i struktura branchy: 5 punktów za zadanie
- Prawidłowe komunikaty commitów: 3 punkty za zadanie
- Poprawne rozwiązanie konfliktów: 10 punktów
- Poprawne wykonanie operacji Git: 5 punktów za zadanie
- Poprawne formatowanie Markdown: 2 punkty za zadanie

## Oddanie
- Wszystkie branche muszą być wypchnięte na zdalne repozytorium
- Prześlij URL swojego forka
- Wszystkie PR muszą być utworzone przed końcem czasu
