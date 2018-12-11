# How to refactor the code

Mozliwe scenariusze i sposoby rozwizania
# zmiana w kodzie, w jednej funkcji, linijce
+ zmiana jednego miejsca w pliku

# wprowadzenie nowej funkcjonalnosci
+ zamiana funkcji poprzez edycje, zastapienie starego kodu

# zmiana sposobu dzialania funkcji
ta sama nazwa ale w innym, nowym pliku klasy
w ten sposob mozna przelaczyc ze starego kodu na nowy, od nowej wersji, z funkcja IF
sa 3 etapy:
version: 1.1.2
+ dzialanie na starej funkcji, stary kod
version: 1.1.3
+ przelaczenie od nowego kodu, poprzez warunek (version > 1.1.2)
version: 1.1.4
+ usuniecie warunku i starego kodu
