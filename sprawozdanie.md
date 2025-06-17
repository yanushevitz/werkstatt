 Sprawozdanie – Baza danych warsztatu samochodowego

## 1. Opis oraz zastosowanie bazy danych

Stworzona baza danych służy do zarządzania warsztatem samochodowym. Umożliwia rejestrowanie klientów, pojazdów, zleceń naprawczych, usług oraz mechaników. Baza pozwala prowadzić ewidencję wykonanych usług oraz monitorowanie ilości zleceń i klientów.

**Zastosowanie:**
- Rejestracja klientów i ich pojazdów
- Tworzenie zleceń naprawczych
- Ewidencja wykonanych usług
- Ułatwienie pracy mechaników i kierowników warsztatu

## 2. Diagram ERD

!["diagram ERD"](diagram-ERD.png)

## 3. Opis poszczególnych kwerend

### Ile napraw w miesiącu
Pokazuje najbardziej problematyczne pojazdy w zestawieniu miesięcznym
### Ile zleceń na mechanika
Pokazuje sumę zleceń przypadającą na jednego mechanika w serwisie malejąco
### Klient z największą flotą
Pokazuje posortowane od największej liczby, sumy pojazdów zarejestrowanych na jednego klienta. Pozwala to znaleźć najbardziej lojalnych klientów i do nich kierować propozycje zaciśnienia współpracy

## 4 opis raportów
Raporty umożliwiają prezentację danych z bazy w ustrukturyzowanej i czytelnej formie, co jest kluczowe dla analizy, podsumowań oraz celów sprawozdawczych. Z poziomu tej bazy danych możliwe jest generowanie następujących typów raportów:
## 4.1. Raport zleceń według mechaników
- Przeznaczenie: Raport ten przedstawia zbiorcze dane dotyczące liczby pojazdów naprawionych przez każdego mechanika w wybranym okresie sprawozdawczym.
- Co się w nim znajduje: Nazwisko mechanika oraz łączna liczba aut, które serwisował.
- Funkcja: Służy do oceny indywidualnej efektywności pracy, wspiera procesy rozliczeniowe oraz planowanie kadrowe.
## 4.2. Raport usług
- Przeznaczenie: Dokumentuje pełną listę wszystkich usług oferowanych przez warsztat.
- Co się w nim znajduje: Nazwa usługi, jej jednostkowa cena oraz szacowany czas wykonania.
- Funkcja: Służy jako oficjalny cennik dla klientów oraz wewnętrzne narzędzie do szybkiego weryfikowania kosztów i czasu trwania poszczególnych czynności.
## 4.3. Raport kliencki
- Przeznaczenie: Stanowi kompleksową kartotekę klienta, zawierającą dane kontaktowe, listę posiadanych pojazdów oraz syntetyczną historię wykonanych dla nich zleceń.
-Co się w nim znajduje: Imię, nazwisko klienta, marka i model jego pojazdu, numer rejestracyjny oraz daty przyjęcia zlecenia wraz z krótkim opisem wykonanych prac.
- Funkcja: Umożliwia kompleksowy przegląd historii serwisowej klienta i jego pojazdów, co sprzyja personalizacji obsługi i budowaniu długoterminowych relacji.
## 4.4. Raport zleceń ogólny
- Przeznaczenie: Zapewnia przegląd wszystkich zarejestrowanych zleceń,    zarówno tych w trakcie realizacji, jak i historycznych.
- Co się w nim znajduje: Numer identyfikacyjny zlecenia, data przyjęcia pojazdu, marka i model pojazdu, nazwisko mechanika odpowiedzialnego za naprawę oraz opis zgłoszonych usterek.
- Funkcja: Służy do ogólnego monitorowania działalności warsztatu, ułatwia wyszukiwanie konkretnych zleceń oraz jest bazą do generowania zbiorczych statystyk operacyjnych.



## 5. Opis formularzy

Formularze w bazie danych umożliwiają wygodne zarządzanie informacjami:
- Formularz do dodawania klientów
- Formularz do wprowadzania pojazdów
- Formularz tworzenia zleceń i usług
- Formularz do wprowadzania mechaników
- Formularz do dołączania usług do zleceń (są one osobno)

## 6. Podział pracy

| Osoba             | Zakres wykonanej pracy                                |
|-------------------|--------------------------------------------------------|
| Kacper Mucha      | Projekt bazy danych, relacje              |
| Mateusz Walczak        | Formularze, dokumentacja                           |
| Kacper Janusz  | Kwerendy, diagram ERD                 |
