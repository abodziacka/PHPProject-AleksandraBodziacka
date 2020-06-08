#### Bodziacka Aleksandra
#### Brzozowska Marta
#
#
# Web_Library
> Program zostanie stworzony w celu elektronicznego wypo�yczenia ksi��ek z biblioteki.
Do oprogramowania maj� dost�p zar�wno klienci biblioteki, kt�rzy mog� z�o�y� swoje zam�wienie, jak i jej pracownicy, kt�rzy maj� mo�liwo�� edycji bazy danych.

## Spis tre�ci
* [Cele systemu](#cele-sytemu)
* [U�ytkownicy](#uzytkownicy)
* [Techologie](#technologie)
* [Funkcjonalno�ci](#funkcjonalno�ci)
* [Diagram UML](#diagram-uml)
* [Kontakt](#kontakt)

## Cele systemu
Przeznaczenie systemu: mo�liwo�� internetowego wypo�yczenia ksi��ek w stacjonarnej bibliotece. Aplikacja daje gwarancje u�ytkownikowi na wcze�niejsze zarezerwowanie ksi��ek przed osobist� wizyt�.
Dodatkowo system jest pomoc� dla bibliotekarzy, kt�rzy w sprawny spos�b mog� edytowa� baz� ksi��ek oraz na odleg�o�� informowa� klient�w o dost�pno�ci poszczeg�lnych ksi��ek.

## U�ytkownicy
U�ytkownicy aplikacji dziel� si� na 2 grupy:
* ***Klienci*** - osoby zainteresowane wypo�yczeniem (zarezerwowaniem) danej ksi��ki. Mog� przegl�da� dost�pne ksi�zki, czyta� opisy ksi��ek, jak i wypo�ycza�.
* ***Bibliotekarze*** - mog� edytowa� baz� ksi��ek (dodawa�, usuwa�, zaznacza� dost�pno��) oraz maj� wgl�d do kont wypo�yczaj�cych (zaznaczaj� wypo�yczenie-gdy osoba przychodzi do bliblioteki po ksi��k�, jak i oddanie- gdy j� zwraca).

## Technologie
* Framework PHP MVC Symfony

## Funkcjonalno�ci
Funkcjonalno�ci serwisu podzielone s� na 2 grupy: funkcjonalno�ci u�ytkownika oraz admina (bibliotekarza).
##### Funkcjonalno�ci u�ytkownika
* Przegl�danie dost�pno�ci ksi��ek
* Przegl�danie autor�w 
* Czytanie opis�w dot. danej ksi��ki
* Przegl�danie kategorii
* Wypo�yczenie (zarezerwowanie) danej ksi��ki

##### Funkcjonalno�ci admina
* Usuwanie ksi��ki z bazy danych
* Dodawanie ksi��ki do bazy danych
* Usuwanie autora z bazy danych
* Dodawanie autora do bazy danych
* Modyfikowanie dost�pno�ci ksi��ek
* Zaznaczanie wypo�yczenia i oddania ksi��ki przez klienta

##### Model MVC
Wszystkie te funkcjonalno�ci przedstawione b�d� za pomoc� wzorca architektonicznego MVC (model-view-controller).
> ***Model*** -  odpowiedzialny jest za komputerow� reprezentacj� problemu zawiera funkcje, kt�re s� dost�pne w danym oprogramowaniu (w nim zadeklarujemy wszystkie zmienne oraz obiekty potrzebne do wykoanania aplikacji).

>***Widok*** - jest odpowiedzialny za prezentacj� danych w obr�bie graficznego interfejsu u�ytkownika (dzi�ki niemu klient     b�dzie mia� mo�liwo�� wybor�w poszczeg�lnych opcji).
    * Przegl�danie dost�pno�ci ksi��ek
    * Przegl�danie autor�w 
    * Czytanie opis�w dot. danej ksi��ki
    * Przegl�danie kategorii

>***Kontroler*** - odbiera i przetwarza dane wej�ciowe u�ytkownika (jest ��cznikiem mi�zy widokiem a modelem, czyli dzi�ki     niemu program b�dzie wiedzia� jakie informacje wyci�gn�� z modelu po akcji u�ytkownika).
    * Wypo�yczenie (zarezerwowanie) danej ksi��ki
    * *Usuwanie ksi��ki z bazy danych
    * Dodawanie ksi��ki do bazy danych
    * Usuwanie autora z bazy danych
    * Dodawanie autora do bazy danych
    * Modyfikowanie dost�pno�ci ksi��ek
    * Zaznaczanie wypo�yczenia i oddania ksi��ki przez klienta
## Diagram UML
![diagram_uml](./img/uml.png)
![diagram2_uml](./img/uml2.png)

## Kontakt
Created by [AleksandraBodziacka](olabodziacka.op.pl) & [MartaBrzozowska](marta_brzozowska@icloud.com)- feel free to contact us!