# Simple-calculator  -  A simple calculator written using HTML, CSS and JS.

Poniżej przedstawiam opis poszczególnych funkcji w JS kodzie / funkcjonalność strony:

1. ``insert(num)``:
-Ta funkcja dodaje liczbę lub operator do wyświetlacza kalkulatora.
-Jeśli właśnie przeprowadzono obliczenie (co wskazuje zmienna ``justCalculated``), wyświetlacz jest wyczyszczony, a ``justCalculated`` ustawiane jest na ``false``.
Funkcja sprawdza, czy dodana liczba to kropka dziesiętna i zapewnia, że w bieżącym wyrażeniu liczbowym jest tylko jedna kropka dziesiętna.

2. ``equal()``:
Oblicza wynik wyrażenia matematycznego wyświetlanego na kalkulatorze.
Pobiera bieżące wyrażenie z wyświetlacza kalkulatora.
Wykonuje obliczenia i zapisuje wynik.
Wynik jest sformatowany tak, aby mieścił się w 12 cyfrach na wyświetlaczu.
Zmienna ``justCalculated ``jest ustawiana na ``true``, ponieważ właśnie przeprowadzono obliczenie.

3. ``clean()``:
Ta funkcja czyści wyświetlacz kalkulatora.

4. ``squareRoot()``:
Oblicza pierwiastek kwadratowy z liczby.
Pobiera bieżące wyrażenie z wyświetlacza kalkulatora.
Oblicza pierwiastek kwadratowy i wyświetla wynik.
Jeśli wynik nie jest liczbą (``NaN``), wyświetlane jest ostrzeżenie.

5. ``square()``:
Podnosi liczbę do kwadratu.
Pobiera bieżące wyrażenie z wyświetlacza kalkulatora.
Oblicza kwadrat liczby i wyświetla wynik.

6. ``percent()``:
Oblicza procent z liczby.
Pobiera bieżące wyrażenie z wyświetlacza kalkulatora.
Wyświetla wynik jako procent.

7.``formatResult(result)``:
Ta funkcja odpowiada za sformatowanie wyniku tak, aby mieścił się w 12 cyfrach na wyświetlaczu kalkulatora.
Przyjmuje wynik (``result``) jako argument.
Jeśli wynik jest liczbą całkowitą (liczbą całkowitą), zostaje zwrócony bez zmian.
Jeśli wynik jest ułamkiem lub liczbą dziesiętną, zostaje zaokrąglony, aby zmieścić się w 12 cyfrach.
Funkcja dba o to, aby wynik był wyświetlany w zwięzły i czytelny sposób.
