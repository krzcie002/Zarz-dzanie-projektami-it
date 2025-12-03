
# Project Charter — Domowy Tracker Wydatków (DTW)

## Cel (SMART)
Do **15 grudnia 2025** dostarczyć uproszczoną wersję aplikacji DTW umożliwiającej:
- dodawanie wydatków,
- przeglądanie listy wydatków z ostatnich 30 dni,
- wyświetlenie sumy wydatków miesięcznych
- kategoryzacja(jedzenie, rachunki)

Czas rejestracji pojedynczego wydatku ≤ 15s; błędy krytyczne ≤ 1/100 uruchomień.

## Zakres (in/out)
**IN:** prosty backend (Python), pamięć in‑memory/plik, UI do dodawania i przeglądania wydaktów, testy jednostkowe, CI.
**OUT:** zarządzanie przychodami i budżetami, integracje bankowe - zewnętrzne API, logowanie użytkowników, synchronizacja danych między urządzeniami, statystyki i wykresy do podejrzenia.

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

## Założenia
- Zespół 3-4 osoby,
- Czas trwania 2-3 tygodnie,
- użytkownik korzysta z aplikacji na jednym urządzeniu,

## Ograniczenia
- Brak prawdziwej bazy danych i logowania.
- Brak backupu,
- minimalizm

