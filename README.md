# JavScript i JSON
### _Podstawy Javascript i format wymiany danych JSON_, **zjazd 3** `2019 XII 07`

### JavaScript
* historia i cel
* typy danych, zmienne i stałe
  - wbudowane (proste) typy danych
  - rozbudowane typy: tablice i obiekty, pozwalające na zbudowywanie dowolnej struktury
  - zagnieżdzanie struktury danych
* konstrukcje języka
  - operatory
  - pętle (while, while-do, for, for-of, for-in)
  - wyrażenia warunkowe (if, if/else, operator trójkowy)
  - funkcje
  - funkcje/metody dla poszczególnych typów danych (np. dla tablic lub ciągów tekstowych)
  - wyrażenia regularne
  - zakresy zmiennych
  - this
  - Promise
  - fetch
  
_____

## JavScript i JSON - lista zadań

### Reverse (1)
Napisz funkcję _reverse_, która przyjmuje ciąg znaków, odwraca w nim kolejność liter, a następnie zwraca go.\
Na przykład: “Alfabet” → “tebaflA”.

[Rozwiązanie dla tego zadania (0/1)](#)

---
### Title Case (2)

Napisz funkcję _toTitleCase_, która przyjmuje ciąg znaków, zamienia pierwszą literę każdego wyrazu na wielką. Pozostałe litery zamienia na małe, a następnie zwraca go.\
Na przykład: “jan Maria ROKITA” → “Jan Maria Rokita”

[Rozwiązanie dla tego zadania (0/1)](#)

---
### Tell Time (3)
Napisz funkcję _tellTime_, która co sekundę wypisuje do konsoli aktualny czas w formacie `HH:MM:SS`. Wykorzystaj wbudowaną w przeglądarkę funkcję _setTimeout_, albo _setInterval_.\
Na przykład: “07:35:12”, “22:05:02”, “00:01:17”, itp.

[Rozwiązanie dla tego zadania (0/1)](#)

---
### Shuffle (4)
Napisz funkcję _shuffle_, która przyjmuje tablicę, a następnie zwraca jej kopię z losowo przemieszanymi elementami.\
Na przykład: [12, 34, 56, 67] → [34, 67, 12, 56]

[Rozwiązanie dla tego zadania (0/1)](#)

---
### Union (5)
Napisz funkcję _union_, która przyjmuje dwie tablice, a następnie zwraca nową tablicę będącą ich sumą, tj. zawierającą elementy obu tablic, bez powtórzeń. Kolejność bez znaczenia.\
Na przykład: [“a”, “e”, “g”, “b”] oraz [“c”, “g”, “a”] → [“a”, “e”, “g”, “b”, “c”]

[Rozwiązanie dla tego zadania (0/1)](#)

---
### Intersection (6)
Napisz funkcję _intersection_, która przyjmuje dwie tablice, a następnie zwraca nową tablicę zawierającą tylko te elementy, które występują w obu tablicach równocześnie. Kolejność bez znaczenia.\
Na przykład: [“a”, “a”, “d”, “f”] oraz [“g”, “d”, “a”] → [“a”, “d”]

[Rozwiązanie dla tego zadania (0/1)](#)

---
### Secret Number (7)
Napisz funkcję _secretNumber_, która losuje liczbę od 1 do 100, a następnie prosi gracza o odgadnięcie tej liczby. Wykorzystaj wbudowaną w przeglądarkę funkcję _prompt_, aby umożliwić graczowi podanie zgadywanej liczby. Po każdej próbie odgadnięcia liczby informuj gracza przy pomocy wbudowanej w przeglądarkę funkcji alert o tym, czy zgadywana liczba jest większa, czy mniejsza od tej podanej przez gracza.

[Rozwiązanie dla tego zadania (0/1)](#)
