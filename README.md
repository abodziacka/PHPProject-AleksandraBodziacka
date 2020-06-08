#### Bodziacka Aleksandra
#### Brzozowska Marta
#
#
# Web_Library
> Program zostanie stworzony w celu elektronicznego wypo¿yczenia ksi¹¿ek z biblioteki.
Do oprogramowania maj¹ dostêp zarówno klienci biblioteki, którzy mog¹ z³o¿yæ swoje zamówienie, jak i jej pracownicy, którzy maj¹ mo¿liwoœæ edycji bazy danych.

## Spis treœci
* [Cele systemu](#cele-sytemu)
* [U¿ytkownicy](#uzytkownicy)
* [Techologie](#technologie)
* [Funkcjonalnoœci](#funkcjonalnoœci)
* [Diagram UML](#diagram-uml)
* [Kontakt](#kontakt)

## Cele systemu
Przeznaczenie systemu: mo¿liwoœæ internetowego wypo¿yczenia ksi¹¿ek w stacjonarnej bibliotece. Aplikacja daje gwarancje u¿ytkownikowi na wczeœniejsze zarezerwowanie ksi¹¿ek przed osobist¹ wizyt¹.
Dodatkowo system jest pomoc¹ dla bibliotekarzy, którzy w sprawny sposób mog¹ edytowaæ bazê ksi¹¿ek oraz na odleg³oœæ informowaæ klientów o dostêpnoœci poszczególnych ksi¹¿ek.

## U¿ytkownicy
U¿ytkownicy aplikacji dziel¹ siê na 2 grupy:
* ***Klienci*** - osoby zainteresowane wypo¿yczeniem (zarezerwowaniem) danej ksi¹¿ki. Mog¹ przegl¹daæ dostêpne ksi¹zki, czytaæ opisy ksi¹¿ek, jak i wypo¿yczaæ.
* ***Bibliotekarze*** - mog¹ edytowaæ bazê ksi¹¿ek (dodawaæ, usuwaæ, zaznaczaæ dostêpnoœæ) oraz maj¹ wgl¹d do kont wypo¿yczaj¹cych (zaznaczaj¹ wypo¿yczenie-gdy osoba przychodzi do bliblioteki po ksi¹¿kê, jak i oddanie- gdy j¹ zwraca).

## Technologie
* Framework PHP MVC Symfony

## Funkcjonalnoœci
Funkcjonalnoœci serwisu podzielone s¹ na 2 grupy: funkcjonalnoœci u¿ytkownika oraz admina (bibliotekarza).
##### Funkcjonalnoœci u¿ytkownika
* Przegl¹danie dostêpnoœci ksi¹¿ek
* Przegl¹danie autorów 
* Czytanie opisów dot. danej ksi¹¿ki
* Przegl¹danie kategorii
* Wypo¿yczenie (zarezerwowanie) danej ksi¹¿ki

##### Funkcjonalnoœci admina
* Usuwanie ksi¹¿ki z bazy danych
* Dodawanie ksi¹¿ki do bazy danych
* Usuwanie autora z bazy danych
* Dodawanie autora do bazy danych
* Modyfikowanie dostêpnoœci ksi¹¿ek
* Zaznaczanie wypo¿yczenia i oddania ksi¹¿ki przez klienta

##### Model MVC
Wszystkie te funkcjonalnoœci przedstawione bêd¹ za pomoc¹ wzorca architektonicznego MVC (model-view-controller).
> ***Model*** -  odpowiedzialny jest za komputerow¹ reprezentacjê problemu zawiera funkcje, które s¹ dostêpne w danym oprogramowaniu (w nim zadeklarujemy wszystkie zmienne oraz obiekty potrzebne do wykoanania aplikacji).

>***Widok*** - jest odpowiedzialny za prezentacjê danych w obrêbie graficznego interfejsu u¿ytkownika (dziêki niemu klient     bêdzie mia³ mo¿liwoœæ wyborów poszczególnych opcji).
    * Przegl¹danie dostêpnoœci ksi¹¿ek
    * Przegl¹danie autorów 
    * Czytanie opisów dot. danej ksi¹¿ki
    * Przegl¹danie kategorii

>***Kontroler*** - odbiera i przetwarza dane wejœciowe u¿ytkownika (jest ³¹cznikiem miêzy widokiem a modelem, czyli dziêki     niemu program bêdzie wiedzia³ jakie informacje wyci¹gn¹æ z modelu po akcji u¿ytkownika).
    * Wypo¿yczenie (zarezerwowanie) danej ksi¹¿ki
    * *Usuwanie ksi¹¿ki z bazy danych
    * Dodawanie ksi¹¿ki do bazy danych
    * Usuwanie autora z bazy danych
    * Dodawanie autora do bazy danych
    * Modyfikowanie dostêpnoœci ksi¹¿ek
    * Zaznaczanie wypo¿yczenia i oddania ksi¹¿ki przez klienta
## Diagram UML
![diagram_uml](./img/uml.png)
![diagram2_uml](./img/uml2.png)

## Kontakt
Created by [AleksandraBodziacka](olabodziacka.op.pl) & [MartaBrzozowska](marta_brzozowska@icloud.com)- feel free to contact us!