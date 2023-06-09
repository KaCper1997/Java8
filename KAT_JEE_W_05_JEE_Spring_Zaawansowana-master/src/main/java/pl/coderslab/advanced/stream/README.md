![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/152855/73064373-5ed69780-3ea1-11ea-8a71-3d370a5e7dd8.png)


## Zadanie 1 - rozwiązywane z wykładowcą

1. Napisz program, który przy wykorzystaniu strumieni danych, dla podanej listy obiektów typu `String`:

- wypisze na ekranie wielkimi literami wszystkie łańcuchy zaczynające się na literę „a” lub „s”, posortowane alfabetycznie 
- zwróci listę, która powstanie poprzez wybranie z listy unikalnych łańcuchów o długości równej 5
- utworzy obiekt typu `String`, zbudowany z posortowanych elementów listy ograniczonych do 3 pierwszych znaków każdego elementu, oddzielonych przecinkami

## Zadanie 2 - rozwiązywane z wykładowcą

2. Napisz program, który będzie posiadał klasę reprezentującą pracownika `Employee`, zawierającą atrybuty takie jak `imię`, `nazwisko`, `płeć`, `data urodzenia`, `wysokość wynagrodzenia`.
 Utwórz kilka obiektów klasy `Employee`, a następnie:
- wypisz na ekranie wszystkich pracowników, których nazwisko zaczyna się na literę „N”
- wypisz na ekranie wszystkich pracowników, którzy są w wieku między 30 a 45 lat
- daj 5% podwyżki wszystkim kobietom, które są w wieku między 20 a 30 lat, a ich wynagrodzenie jest nie wyższe niż 3500 zł. 

## Zadanie 3

1. Na podstawie podanej listy:
````java
List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5, 6, 7, 8, 9);
````
utwórz listę, której elementy będą spełniać następujące warunki:
- kwadrat wartości pomniejszony o 5 będzie mniejszy od 20,
wykorzystaj gotowe wyrażenia lambda:
````
n -> n * n - 5
````
oraz:
````
n -> n < 20
````

## Zadanie 4

1. Stwórz listę elementów typu `String`, następnie utwórz strumień, który:
- wypisze na konsoli długości elementów listy
- zwróci listę posortowaną alfabetycznie 
- wypisze na konsoli elementy, które zawierają literę „c”
- zwróci sumę długości wszystkich elementów
- zwróci 3 pierwsze elementy posortowane alfabetycznie 


## Zadanie 5

1. Stwórz listę elementów typu `String`, następnie utwórz strumień, który przekształcisz do postaci mapy:
````
Map<String, String>
````
gdzie kluczem będzie pierwotny napis, a wartością napis pisany od tyłu.
