
# Project Charter — Domowy Tracker Wydatków (DTW)

## Cel (SMART)
Do **15 grudnia 2025** dostarczyć uproszczoną wersję aplikacji DTW umożliwiającej:
- dodawanie wydatków,
- przeglądanie listy wydatków z ostatnich 30 dni,
- wyświetlenie sumy wydatków miesięcznych
- kategoryzacja(jedzenie, rachunki)

Czas rejestracji pojedynczego wydatku ≤ 15s; błędy krytyczne ≤ 1/100 uruchomień.

## Zakres (in/out)
**IN:** prosty backend (Python), lokalna baza danych, logowanie użytkowników, UI do dodawania i przeglądania wydaktów, testy jednostkowe, CI.
**OUT:** zarządzanie przychodami i budżetami, integracje bankowe - zewnętrzne API, aplikacja postawiona na serwerze/hostingu, prawdziwa baza danych, synchronizacja danych między urządzeniami, statystyki i wykresy do podejrzenia, edycja wydatków.

## Interesariusze
- Zleceniodawca (prowadzący) – ustalenie wymagań, priorytety i akceptacja.
- PM zespołu studenckiego – prowadzenie backlogu.
- Zespół dev/test/DevOps – implementacja i jakość.
- Użytkownik końcowy - osoba odpowiadająca za wydatki domowe.

## Kryteria sukcesu
- Przejście demo i akceptacja kryteriów z `docs/ACCEPTANCE_CRITERIA.md`.
- Użytkownik jest w stanie korzystać z podstawowych funkcji aplikacji bez pomocy dokumentacji
- Zielone pipeline’y w CI.
- Dokumentacja ukończona.
- Działające funkcje MUST

## Założenia
- Zespół 3-4 osoby,
- Czas trwania 2-3 tygodnie,
- użytkownik korzysta z aplikacji na jednym urządzeniu,

## Ograniczenia
- Tylko lokalna baza danych
- Brak backupu,
- minimalizm

