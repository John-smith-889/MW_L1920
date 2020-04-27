# Modelowanie Wieloagentowe [234900-0286], lato 2019/20


## Prowadzący:
* Wykłady: Bogumił Kamiński, http://www.bogumilkaminski.pl
* Ćwiczenia: Łukasz Kraiński, lukasz.krainski123@gmail.com


## Plan zajęć


|Termin ćwiczeń |Ćwiczenia|
|---------------|---------|
|28-04-20 | Asymetria informacji i ograniczona racjonalność w symulacji wieloagentowej|
|05-05-20 | DifPy: propagacja informacji w sieciach społecznych|
|12-05-20 | Modele automatów komórkowych|
|19-05-20 | Uczenie ze wzmocnieniem: wprowadzenie i proces decyzyjny Markowa|
|26-05-20 | Uczenie ze wzmocnieniem: metody Monte Carlo|
|02-06-20 | Prezentacja modelu symulacyjnego 1|
|09-06-20 | Prezentacja modelu symulacyjnego 2|


## Literatura

* Kamiński B. (2012), Podejście Wieloagentowe do Modelowania Rynków. Metody i Zastosowania, Oficyna Wydawnicza Szkoła Główna Handlowa w Warszawie
* Dodatkowa: B. Kamiński, P. Szufel: Julia 1.0 Programming Cookbook, Packt Publishing, 2018 (https://www.packtpub.com/application-development/julia-10-programming-cookbook)


## Zasady zaliczenia

* Rozwiązania prac domowych (maksymalnie 30 punktów): **trzy** wybrane prace domowe - proszę zamieścić pliki z rozwiązaniami na repozytorium na GitHubie (preferowane pliki `.ipynb` albo skrypt z kodem i plik `.pdf/.html` z raportem) i przesłać link na lukasz.krainski123@gmail.com

* Raport i prezentacja z budowy modelu symulacyjnego (maksymalnie 70 punktów)

Punktacja a ocena końcowa
|Od |Do|Ocena|
|---|--|------|
|0 |49 |Niedostateczny|
|50 |59 |Dostateczny|
|60 |69 |Dostateczny plus|
|70 |79 |Dobry|
|80 |89 |Dobry plus|
|90 |100 |Bardzo dobry|


## Zasady dotyczące modelu symulacyjnego

### Praca grupowa
Projekt należy wykonać w zespołach maksymalnie 3-osobowych. Skład i nazwy zespołów proszę wysłać na lukasz.krainski123@gmail.com  do **05-05-2020 EOD**. Po otrzymaniu wszystkich zgłoszeń, zespoły zostaną losowo przydzielone do prezentowania 2. lub 9. czerwca. Daty prezentowania wraz z nazwami zespołów pojawią się w poniższym pliku README.

### Terminy
Prezentacje należy przygotować do dnia prezentowania (ewentualna improwizacja na żywo również jest możliwa, ale nie jest zalecana). Niezależnie od dnia prezentaji, wszystkie pliki (prezentację, kod, raport) należy spakować i przesłać do **09-06-2020 EOD** na lukasz.krainski123@gmail.com.

### Pliki i wysyłka


Paczka przesłana w mailu powinna zawierać:
* plik z prezentacją `.pdf`, `.pptx`, itd.
* plik raportu `.pdf` lub `.html`
* pliki robocze:
    * plik `.ipynb` LUB
    * skrypty `.jl/.py` oraz plik z opisem i wykresami np. `.docx`

### Tematyka modeli

Modele mogą mieć dowolną tematykę związaną z modelowaniem wieloagentowym. Ważne jest, aby posiadały odpowiedni stopień złożoności pozwalający na wielowymiarową analizę zachodzących procesów na skutek zmiany parametrów wejściowych.

Przykładowe tematy modeli:

* Modele oparte na grafach (rozprzestrzenianie się chorób/informacji)
* Systemy kolejkowe
* Automaty komórkowe, "Game Of Life", predator-prey
* Modele Reinforcement Learning (Actor-Critic, Q-Learning, OpenAI Gym)

### Struktura raportu

Struktura raportu:
* Wstęp: opis zagadnienia, założenia modelu, wzory, parametry, spodziewane wyniki
* Implementacja: opis kodu modelu (komentarze w kodzie/opisy w komórkach - nie musi to być opis linijka po linijce, raczej opis logicznych bloków kodu)
* Analiza: wyniki symulacji i zmian zachodzących przy zmianie parametrów wejściowych (przedstawienie graficzne i opisowe)
* Podsumowanie: wnioski i zauważone prawidłowości

### Wymagany język

Python lub Julia

### Punktacja

Projekt będzie oceniany całościowo, poniższa punktacja jest zamieszczona poglądowo, aby wiedzieli Państwo jaką wagę mają poszczególne elementy.

Kod (czytelność, poprawność, agenci jako obiekty `struct/class`): `25pkt`

Opis/analiza (odpowiednie przedstawienie graficzne,poprawna interpretacja wyników): `30pkt`

Prezentacja (oprawa graficzna, czytelność, zaciekawienie słuchaczy): `15pkt`
