---
title: Audyt Zakresu projektu grupy "Grafy" (1.1)
author: Jan Orlik i Radosław Kapłon
header-includes:
    - \usepackage{fancyhdr}
    - \pagestyle{fancy}
    - \fancyhead[RE,RO]{Audyt zakresu projektu grupy Grafy v1.1 - 18.03.2017}
    - \fancyfoot[CO,CE]{grupa Sealious}
    - \fancyfoot[LE,RO]{\thepage}
---

## Autorzy: 

* Jakub Orlik
* Radosław Kapłon

## Data: 

18.03.2017

## Wersja: 

1.1

\newpage

# Uwagi ogólne

* W treść dokumentu wkradły się liczne błędy składniowe oraz interpunkcyjne, co może być odebrane przez niektórych jako brak staranności.

# Uwagi merytoryczne

* Punkt 4 - "Wymagania Projektowe", podpunkt 2:

	> aplikacja ma zostać utworzona w ustalonych wcześniej technologiach (klient),
	
	zdaje się sugerować, że wybór silnika Unity3D został dokonany przez klienta i klient widzi wartość w używaniu tej technologii. Czy faktycznie klientowi zależy na tym, aby projekt był realizowany w Unity3D? Dodatkowo, jeden z paragrafów punktu "1. Cele projektu":
	
	> Celami pośrednimi jest nauka projektowania aplikacji w środowisku
	> trójwymiarowym oraz lepsze zrozumienie budowy programów służącym celom
	> edukacyjnym.
	
	wskazuje raczej, że wybór Unity3D został dokonany przez wykonawców i był zmotywowany chęcią poznania i nauki tej technologii.

* Przypadki użycia zakładają, że własne grafy są wgrywane do projektu za pomocą plików tekstowych. Składnia tych plików może okazać się punktem zapalnym procesu realizacji programu. Być może nie należy pozostawiać kwestii tego, czy format pliku jest zrozumiały i wygodny w użyciu programistom implementującym jego parsowanie. W planowaniu wczesnych faz projektu należy uwzględnić czas na uzgadnianie z klientem tej składni, aby uniknąć zmian w późniejszych fazach realizacji.

	Być może warto zapoznać się z językiem DOT, który został stworzony dokładnie do opisów grafów. Jest otwartym standardem opartym o pliki tekstowe.
	
	> https://en.wikipedia.org/wiki/DOT_(graph_description_language)

* "Punkt 11 - Kamienie milowe" nie przewiduje określonych jako "ważną część projektu" funkcjonalności pomocy teoretycznej

* Skrócony przypadek użycia #6: "Zatrzymanie działania algorytmu i manipulacja jego krokami" mówi:

	> [Użytkownik] w dowolnym momencie może zmienić miejsce do którego algorytm wyszukuje ścieżkę
	
	To może być problematyczne w przypadku reprezentacji algorytmów, które w trakcie działania odrzucają pewne krawędzie i prowadzić do błędnych rezultatów. Przypadek użycia powinien albo zawierać opis tego, jak zostanie to zakomunikowane użytkownikowi albo nie zawierać tej możliwości.
	
* Z przypadków użycia nie wynika jasno, czy reprezentacja działania algorytmu odbywa się w sposób ciągły ("wciśnij play i oglądaj"), czy krokowy ("wciśnij guzik aby pokazać następny krok algorytmu"). Kawałek z przypadku #6:

	> Aby to zrobić, użytkownik musi w odpowiednim momencie nacisnąć klawisz odpowiedzialny za zatrzymacie algorytmu.

	Zdaje się sugerować pierwszą opcję - która zdaje się w pewien sposób narzucać użytkownikowi tempo analizy algorytmu. Czy klient o tym wie? Należy to uściślić i umieścić w zakresie.
	
* [drobna uwaga] "Punkt 5 - Granice Projektu" mówi: 

	> Nie będzie tu możliwości importowania wyników działania innych programów oferujących usługi związane z grafami
	
	Można założyć, że w przyszłości ktoś stworzy program, który pozwoli generować pliki tekstowe opisujące grafy w sposób zrozumiały dla programu opisywanego w audytowanym dokumencie (obsługa takich plików mieści się w zakresie projektu). W takim wypadku *będzie* istniała możliwość importowania wyników innego programu.

* Uwaga odnośnie harmonogramu: harmonogram prac przewiduje czas na zaimplementowanie wizualizacji, ale nie przewiduje czasu na jej *projektowanie*. Mimo, że klient wymaga aby "aplikacja ma być prosta w obsłudze, interfejs ma być czytelny i nie sprawiać problemów podczas działania". Bez poświęcenia czasu na projektowanie przejrzystego interfejsu może być ciężko osiągnąć taki rezultat.

* Punkt "7. Ograniczenia projektowe" opisuje tylko potencjalne ryzyko, jakie powoduje korzystanie z Unity3D. Jego aktualna zawartość powinna naszym zdaniem znaleźć się punkcie "Ryzyka zidentyfikowane w fazie początkowej", a w jego miejscu powinna znaleźć się analiza faktycznych ograniczeń czasowych/budżetowych/jakościowych (lub ich braku).

* Punkt "10. Ryzyka zidentyfikowane w fazie początkowej" opisuje funkcjonalności, które być może nie zostaną wdrożone. Zdaje się, że warto ustalić z klientem, które funkcjonalności są wymagane, a które opcjonalne, a ten punkt zakresu poświęcić na opis zagrożeń dla samego procesu realizacji projektu.

* W zakresie projektu nie znalazło się wytłumaczenie, w jaki sposób grafika 3D pomoże zrozumieć działanie algorytmu, zamiast utrudniać ten proces. Nie jest wytłumaczone, jakie kryteria musi spełniać wizualizacja, aby zapewnić "czytelniejsze przekazanie informacji". Mając na uwadze, że jest więcej sposobów, w jaki grafika 3D może zmniejszyć czytelność informacji niż ją zwiększyć, zdecydowanie przydałoby się ten aspekt doprecyzować i przewidzieć w harmonogramie projektu czas poświęcony na projektowanie czytelnej reprezentacji.

