---
title: "Dokumentacja frameworka Sealious - karta projektu"
author: Jan Orlik i Radosław Kapłon
header-includes:
    - \usepackage{fancyhdr}
    - \pagestyle{fancy}
    - \fancyhead[RE,RO]{Dokumentacja Sealious - Karta projektu v1 - 24.03.2017}
    - \fancyfoot[CO,CE]{grupa Sealious}
    - \fancyfoot[LE,RO]{\thepage}
	- \renewcommand{\familydefault}{\sfdefault}
language: pl-PL
---


# Cel projektu

Celem projektu jest rozwiązanie następującego problemu:

> Przez ostatnie kilka miesięcy rozwój frameworka Sealious był wysoce niezorganizowany i chaotyczny, co doprowadziło do powstania wielu przydatnych, ale nieudokumentowanych funkcji. Większa część zespołu programistów nie wie, jak używać albo modyfikować te funkcjonalności.

# Potrzeby biznesowe 

Framework Sealious jest jednym z głównych narzędzi programistycznych wykorzystywanych w zespole Sealcode. Umożliwia szybkie tworzenie wysokiej jakości aplikacji internetowych. Kluczowe dla Sealcode'u jest, aby Sealious był łatwy w użyciu, a struktura jego kodu zrozumiała dla osób pracujących nad nim.

# Uzasadnienie biznesowe

* **podsumowanie**: stworzenie dokumentacji Sealiousa pomoże efektywniej realizować zlecenia komercyjne, które umożliwią pozyskanie funduszy na realizowanie celów statutowych inicjatywy. 
* **powody podjęcia projektu**: obserwacja, że coraz mniej osób w zespole rozumie, jak działa Sealious
* **możliwe rozwiązania**:
  - *nie robić nic*: licząc na to, że zespół przestudiuje uważnie kod frameworka i zrozumie jego działanie. Takie rozwiązanie nie będzie sprzyjało wdrażaniu nowych osób do zespołu
  - *udokumentować aktualną wersję Sealiousa*
  - *stworzyć nową, hipotetyczną dokumentację Sealiousa*, po czym napisać go od podstaw w zgodzie z nią
* **oczekiwane korzyści**: możliwość szybszego (przez co: tańszego) wykonywania zleceń komercyjnych i nie tylko
* **przewidywane niepożądane skutki**: brak
* **terminy**: rezultatów można spodziewać się latem 2017
* **koszty**: tylko wkład osobowy członków zespołu, działających charytatywnie (Sealious jest projektem open-source)
* **główne ryzyka**: nie zidentyfikowano

# Opis produktu projektu

Dokumentacja hipotetycznej wersji Sealiousa, wg której zostanie potem zaimplementowany Sealious. Na dokumentację mają składać się:

* dokumentacja użytkowa,
* dokumentacja techniczna,
* testy integracyjne
* część testów jednostkowych

# Wymagania które muszą być spełnione aby zadowolić interesariuszy

Dokumentacja ma być dostępna w postaci pdf, html (dostępne z publicznego serwera), oraz MD (dostępne z poziomu repozytorium).

Dokumentacja ma być napisana w języku polskim. 

Dokumentacja ma czytelnie i skutecznie tłumaczyć mechanikę działania Sealiousa i sposób jego użytkowania.

# Wpływ interesariuszy na projekt

* programiści Sealcode: tworzą dokumentację, są też jej docelowymi odbiorcami

# Zaangażowanie innych struktur organizacyjnych danej instytucji na projekt

Nie dotyczy.

# Założenia projektowe

* programiści Sealcode mają czas aby spotkać się co najmniej raz w tygodniu (online lub offline) 
* programiści mają dostęp do współdzielonego repozytorium, w którym umieszczane są zmiany w dokumentacji
* programiści mają dostęp do narzędzia umożliwiającego "Review" kodu

# Kamienie milowe

1. Dokumentacja API Sealiousa - do końca marca 
2. Przykłady użycia Sealiousa - do końca kwietnia
3. Testy jednostkowe - do końca maja
4. Testy integracyjne - do końca czerwca

# Wstępny budżet

Nie dotyczy.

# Nazwisko kierowników projektu i ich zakres kompetencji

* Kuba Orlik - komunikacja z zespołem
* Radosław Kapłon - zarządzanie dokumentami, nadzór tempa wykonywania projektu
