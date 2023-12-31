# SQL Database Projekt Kino

Relacyjny model bazy danych Kina Zeus. 


## Opis studium

Klient kina dokonuje rezerwacji biletu, możliwe ma do wyboru dwie opcje: internetowo lub stacjonarnie. Jeżeli rezerwuje bilet internetowo musi podać oprócz imienia i nazwiska, e-mail. W przypadku stacjonarnego zakupu podaje tylko imię i nazwisko.
Rezerwacji biletu dokonuje pracownik, który w danym momencie jest odpowiedzialny za obsługę widza (może on nabić zniżkę na bilet, w zależności od wieku klienta). Pracownik jest również przypisany do odpowiedniego dyżuru, który wyznacza salę, którą sprząta i przygotowuje do seansu pracownik. Każda sala ma do siebie przydzielony projektor.
Bilet przypisany jest do konkretnego miejsca, a miejsce do konkretnej sali. Bilet również odpowiada za wyznaczony seans, który wybrał klient. Każdy seans odpowiada za jeden film, który jest odpowiednio opisany. Do każdego filmu przypisany jest konkretny reżyser.




## Model relacyjnej bazy danych

W plikach można zobaczyć model relacyjnej bazy danych. (png)

## Tabele
Zostało utworzonych 11 encji, w tym jedna tabela łącząca:
- Bilety
- Dyżury
- Filmy
- Klienci
- Miejsca
- Pracownicy
- Projektory
- Rezerwacje
- Reżyserzy
- Sale
- Seanse
  
Tabela łącząca: 
- SA_MI


Plik z utworzeniem tabel oraz polecenia DDL służące do wykonania relacji pomiędzy tabelami znajduje się w pliku **CREATE TABLES**

## Wypełnienie tabel danymi

Lista komend wypełniających tabele w pliku **INSERT DATA**

Pliki reżyserzy1 i reżyserzy2 prezentują wygląd tabeli reżyserzy.

## Przypadki użycia bazy danych

Przypadki użycia bazy danych można zobaczyć w pliku **PRZYPADKI UŻYCIA.**
