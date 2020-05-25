#### Bodziacka Aleksandra
#### Brzozowska Marta
#
#
# Web_Library
> Program zostanie stworzony w celu elektronicznego wypożyczenia książek z biblioteki.
Do oprogramowania mają dostęp zarówno klienci biblioteki, którzy mogą złożyć swoje zamówienie, jak i jej pracownicy, którzy mają możliwość edycji bazy danych.

## Spis treści
* [Cele systemu](#cele-sytemu)
* [Użytkownicy](#uzytkownicy)
* [Techologie](#technologie)
* [Funkcjonalności](#funkcjonalności)
* [Diagram URL](#diagram-uml)
* [Kontakt](#kontakt)

## Cele systemu
Przeznaczenie systemu: możliwość internetowego wypożyczenia książek w stacjonarnej bibliotece. Aplikacja daje gwarancje użytkownikowi na wcześniejsze zarezerwowanie książek przed osobistą wizytą.
Dodatkowo system jest pomocą dla bibliotekarzy, którzy w sprawny sposób mogą edytować bazę książek oraz na odległość informować klientów o dostępności poszczególnych książek.

## Użytkownicy
Użytkownicy aplikacji dzielą się na 2 grupy:
* ***Klienci*** - osoby zainteresowane wypożyczeniem (zarezerwowaniem) danej książki. Mogą przeglądać dostępne ksiązki, czytać opisy książek, jak i wypożyczać.
* ***Bibliotekarze*** - mogą edytować bazę książek (dodawać, usuwać, zaznaczać dostępność) oraz mają wgląd do kont wypożyczających (zaznaczają wypożyczenie-gdy osoba przychodzi do bliblioteki po książkę, jak i oddanie- gdy ją zwraca).

## Technologie
* Framework PHP MVC Symfony

## Funkcjonalności
Funkcjonalności serwisu podzielone są na 2 grupy: funkcjonalności użytkownika oraz admina (bibliotekarza).
##### Funkcjonalności użytkownika
* Przeglądanie dostępności książek
* Przeglądanie autorów 
* Czytanie opisów dot. danej książki
* Przeglądanie kategorii
* Wypożyczenie (zarezerwowanie) danej książki

##### Funkcjonalności admina
* Usuwanie książki z bazy danych
* Dodawanie książki do bazy danych
* Usuwanie autora z bazy danych
* Dodawanie autora do bazy danych
* Modyfikowanie dostępności książek
* Zaznaczanie wypożyczenia i oddania książki przez klienta

##### Model MVC
Wszystkie te funkcjonalności przedstawione będą za pomocą wzorca architektonicznego MVC (model-view-controller).
#
***Model*** -  odpowiedzialny jest za komputerową reprezentację problemu zawiera funkcje, które są dostępne w danym oprogramowaniu (w nim zadeklarujemy wszystkie zmienne oraz obiekty potrzebne do wykoanania aplikacji).
#
***Widok*** - jest odpowiedzialny za prezentację danych w obrębie graficznego interfejsu użytkownika (dzięki niemu klient będzie miał możliwość wyborów poszczególnych opcji).
#
***Kontroler*** - odbiera i przetwarza dane wejściowe użytkownika (jest łącznikiem mięzy widokiem a modelem, czyli dzięki niemu program będzie wiedział jakie informacje wyciągnąć z modelu po akcji użytkownika).

## Diagram UML
![diagram_uml](./img/uml.png)
![diagram2_uml](./img/uml2.png)

## Kontakt
Created by [AleksandraBodziacka](olabodziacka.op.pl) & [MartaBrzozowska](marta_brzozowska@icloud.com)- feel free to contact us!
