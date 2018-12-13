# How to refactor the code

# Podejscie do refaktoryzacji
## rewolucyjne - replace old code
kazda stara funkcjonalnosc jest zastepowana nowa

## ewolucyjne - add new code and use it in some case
z reguly systemy rosna i ich funkcjonalnosc rosnie, rzadko rowzoj systemu oznacza mniej funkcji
Skoro jest rpzyrostowa tendencja to zamiast zastepowac cos co dziala, lepiej stworzyc cos co bedzie zalezne od linii czasu:
CO bedzie dzialao przyrostowo tylko w nowej sytuacji, npp gdy zostanie utworzony nowy uzytkownik, to bedzie uzywal nowego interfaceu ale starzy beda mieli to co zastali przy rejestracji
bedzie rownolegle podobna funkcjonalnosc, ale implementowana inaczej, dzieki czemu faza testowa bedzie na malej grupie
i nie bedzie takie skali problemow, gdy okaze sie ze cos nie dziala.

kiedy kazda nowa funkcja zamiast zastepowac kilka starych
tworzy nowe rozwaiaznie jako alternatywe, jako nastepny krok, nie dotykajac starej i nie zastepujach w 100%

## refaktoryzacja 
dotyczy zmiany pewnej czesci kodu, warto przed podjeciem tego zadania wyodrebnic tylko jedna funkcjonalnosc lub jedna czesc z calosci, aby nie byc odpowiedzialnym za 100% i obciazanym na zbyt dlugo.

Po co robic duzo i zmieniac duzo, w wielu przypadkach wystarczy zmieniac malo i wprowadzac abstrakcje krok po kroku w pewnych czesciach, ktore tego wymagaja, a nie tam, gdzie wszystko dziala poprawnie.




Mozliwe scenariusze i sposoby rozwizania
## zmiana w kodzie, w jednej funkcji, linijce
+ zmiana jednego miejsca w pliku

## wprowadzenie nowej funkcjonalnosci
+ zamiana funkcji poprzez edycje, zastapienie starego kodu

## zmiana sposobu dzialania funkcji
ta sama nazwa ale w innym, nowym pliku klasy
w ten sposob mozna przelaczyc ze starego kodu na nowy, od nowej wersji, z funkcja IF
sa 3 etapy:
### version: 1.1.2
+ dzialanie na starej funkcji, stary kod
### version: 1.1.3
+ przelaczenie od nowego kodu, poprzez warunek (version > 1.1.2)
### version: 1.1.4
+ usuniecie warunku i starego kodu



