# Dokumentacja projektu "Dokumentacja Frameworka Sealious"
## Zakres projektu

* Wersja dokumentu: 1.1
* Autorzy: Kuba Orlik, Radosław Kapłon
* Data 13.03.17 r.

## 1. Cele projektu

1. Celem projektu jest uspójnienie w zespole wizji struktury i kierunku rozwoju frameworka Sealious 
2. Rezultatem pracy nad projektem jest szczegółowa dokumentacja opisująca strukturę i API Sealiousa oraz testy jednostkowe pisane w zgodzie z dokumentacją
3. Projekt jest projektem open-source i docelowo będzie używany przez członków grupy Sealcode
4. Projekt będzie udostępniony publicznie i będą z niego korzystali członkowie grupy Sealious 

## 2. Wyszczególnione produkty projektu

1. Dokumentacja API Sealiousa 
2. Przykłady użycia Sealiousa
3. Testy jednostkowe 
4. Testy integracyjne które będzie musiał dawać kod napisany wedle dokumentacji, która stanowi przedmiot tego projektu

## 3. Opis produktów 

### Wymagania użytecznościowe (niefunkcjonalne)

* Podział na wersje aplikacji
* Z jakich części składa się dokumentacja
* Sekcja z pytaniami
* Publicznie dostępna dokumentacja
* Czytelna zarówno dla ludzi jak i komputerów(markdown)
* Przykłady kodów są podświetlone i mają odpowiednią czcionkę
* Strona powinna być responsywna
* Powinna udostępniać wyszukiwanie

### Wymagania merytoryczne (funkcjonalne)

Dokumentacja Sealiousa: 

* jest dokumentacją użytkową, a nie dokumentacją kodu. Kierowana jest do użytkowników Sealiousa (deweloperów), a nie do osób go rozwijających;
* zawiera poradnik prowadzący użytkownika krok po kroku przez proces instalacji Sealiousa i tworzenia aplikacji Sealiousowej;
* zawiera szczegółowy opis API - opis wszystkich funkcji udostępnianych deweloperom, wraz z ich argumentami i przykładami wywołania;
* zawiera artykuł, który opisuje "co zrobić, gdy wyświetla się błąd treści XYZ";
* zawiera dokument kierowany do dev-opsów opisujący jak optymalnie skonfigurować reverse-proxy do współpracy z aplikacją sealiousową;
* zawiera przykładową konfigurację docker-compose dla aplikacji sealiousowej.

## 4. Wymagania projektowe

### Czasowe

Zalecane jest żeby prace nad projektem zakończyły się z końcem czerwca

### Budżetowe

Projekt jest projektem open source robionym za darmo

### Jakościowe

Dokumentacja nie będzie podlegała ocenie pod względem poprawności lingwistycznej i gramatycznej

### Wymagania co do użytych technologii

Dokumentacja powinna być dostępna w postaci plaintext oraz HTML



## 5. Granice projektu

1. Częścią projektu nie jest utrzymanie serwera www, na którym będzie hostowana dokumentacja
2. Przedmiotem projektu jest dokumentacja frameworka Sealious 
3. Przedmiotem projektu nie jest stworzenie frameworka wedle dokumentacji 


## 6. Kryteria akceptacji produktu

Projekt jest zakończony sukcesem, jeżeli po dostarczeniu dokumentacji deweloperowi spoza zespołu rozwijającego Sealiousa będzię on w stanie wykonać przy jego użyciu aplikację internetową


## 7. Ograniczenia projektowe

Osoby pracujące nad tworzeniem dokumentacji są pracującymi studentami więc ilość deweloperogodzin w tygodniu jest bliska 20.

## 8. Organizacja projektu

### Interesariusze projektu

Członkowie zespołu Sealcode

### Członkowie zespołu wykonawczego

* Kuba Orlik - twórca dokumentacji i kierownik projektu
* Radosław Kapłon - kierownik projektu
* Arkadiusz Wieczorek - twórca dokumentacji 
* Adrian Wydmański - twórca dokumentacji 

## 9. Zidentyfikowane ryzyka

Jeżeli zespół na jakieś decyzje odnośnie, których nie może dojść do konsensusu to projekt może nie zakończyć się sukcesem powodując straty czasowe zespołu


## 10. Kamienie milowe

1. Dokumentacja API Sealiousa - do końca marca 
2. Przykłady użycia Sealiousa - do końca kwietnia
3. Testy jednostkowe - do końca maja
4. Testy integracyjne - do końca czerwca
