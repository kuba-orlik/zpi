---
title: "Szacowanie czasu - dokumentacja Sealious v1 - 7.04.2017"
author: Jan Orlik i Radosław Kapłon
header-includes:
    - \usepackage{fancyhdr}
    - \pagestyle{fancy}
    - \fancyhead[RE,RO]{Szacowanie czasu - dokumentacja Sealious v1 - 7.04.2017}
    - \fancyfoot[CO,CE]{grupa Sealious}
    - \fancyfoot[LE,RO]{\thepage}
	- \renewcommand{\familydefault}{\sfdefault}
language: pl-PL
---

# Notatka

W procesie szacowania czasu zespół posłużył się techniką delficką i techniką 3 punktów.

W trakcie szacowania techniką delficką wystarczyły dwie tury, aby osiągnąć konsensus odnośnie przewidywanego czasu wykonania zadań. 

W trakcie szacowania techniką 3 punktów za czas najbardziej prawdopodobny zespół uznawał czas oszacowany za pomocą techniki delfickiej, a czasy optymistyczny i pesymistyczny zostały ustalone w procesie dyskusji o potencjalnych przeszkodach lub ich braku.

Poniżej umieszczone są wyniki szacowania:


## Techniką delficką

1. Stworzenie tekstu dokumentacji 

    1. Ustalenie ogólnej architektury, języka i stylu kodu  - 8h
  
    2. Spisanie wymaganych funkcjonalności - 16h
    
    3. Identyfikacja jednostek kodu realizujących ustalone funkcjonalności (20) - 20h

    4. Stworzenie szczegółowego słownego opisu przeznaczenia każdej ze zidentyfikowanych jednostek (20) - 16h

    5. Zaprojektowanie API zidetyfikowanych jednostek kodu (20) - 20x 4h

    6. Akceptacja tekstu dokumentacji - 4h

2. Pisanie testów jednostkowych
    
    1. Instalacja i wdrożenie frameworka do testów - 6h
    
    2. Zaplanowanie scenariuszy testowania (100) - 100x 0.25h
    
    3. Implementacja scenariuszy testowania (100) - 100x 0.5h
    
    4. Integracja testów jednostkowych z systemem ciągłej integracji - 8h
    
3. Publikacja dokumentacji 
   
    1. Wdrożenie systemu konwersji dokumentów - 4h
    
    2. Postawienie serwera HTTP i domeny WWW - 8h
    
    
## Techniką 3 punktów

```
optymistyczne / pesymistyczny / najbardziej prawdopodobny = szacunek

```

1. Stworzenie tekstu dokumentacji 

    1. Ustalenie ogólnej architektury, języka i stylu kodu 4/16/8 = 8.6h
  
    2. Spisanie wymaganych funkcjonalności - 12/24/16 = 16.6h
    
    3. Identyfikacja jednostek kodu realizujących ustalone funkcjonalności (20) - 10/30/20 = 20h

    4. Stworzenie szczegółowego słownego opisu przeznaczenia każdej ze zidentyfikowanych jednostek (20) - 10/20/13 = 13.6h

    5. Zaprojektowanie API zidetyfikowanych jednostek kodu (20) - 20/90/80 = 71.6h

    6. Akceptacja tekstu dokumentacji - 2/8/4 = 4.3h

2. Pisanie testów jednostkowych
    
    1. Instalacja i wdrożenie frameworka do testów - 2/8/6 = 5.6hh
    
    2. Zaplanowanie scenariuszy testowania (100) - 20/100/25 = 36.6h
    
    3. Implementacja scenariuszy testowania (100) - 20/200/50 = 70h
    
    4. Integracja testów jednostkowych z systemem ciągłej integracji - 2/12/8 = 7.6h
    
3. Publikacja dokumentacji 
   
    1. Wdrożenie systemu konwersji dokumentów - 2/8/4 = 4.3h
    
    2. Postawienie serwera HTTP i domeny WWW - 6/16/8 = 9h

