# MouGame
Mobile game created with C#, Unity

## Cel i założenia
Gra “Mou” jest przeznaczona na urządzenia mobilne. Jej głównym założeniem jest dostarczanie rozrywki. Gra ma być nieskomplikowana dla użytkownika, aby móc korzystać z niej w chwilach takich jak podróżowanie komunikacją miejską, oczekiwanie w kolejce w przychodni czy podczas przerwy między zajęciami. “Mou” zawiera kilka różnych poziomów, dzięki czemu gracz może wybrać sobie najbardziej odpowiadającą mu rozgrywkę. Gra przyciąga również uwagę ciekawą oprawą wizualną. Na potrzeby gry został wykreowany cały świat gry. Zastosowane zostały oryginalne elementy nawiązujące do tematyki roślin, gór, chmur.

Gra zaczyna się zarysowaniem tła historycznego fabuły. Ukazane zostają slajdy wypełnione tekstem i obrazkami, które wprowadzają gracza w nowy świat. Następnie użytkownik przenoszony jest do panelu, w którym wybiera poziom gry. Celem gry jest przejście przez wszystkie etapy gry. Gracz poprzez zwiększanie swoich wyników i zbieranie bonusów próbuje pomóc tytułowemu bohaterowi gry i zaprowadzić go do domu.

## Technologie
* C#
* Unity 2D

## Uruchomienie
Repozytorium nie zawiera całego, kompletnego projektu. W folderze "Scripts" znajdują się tylko pliki z kodem .cs. 
Mają one za zadanie ukazać, jak zostały rozwiązane funkcjonalności i mechanizmy gry.

## Zespół
Projekt był realizowany w zespole dwuosobowym, w którym odpowiadałam m. in. za:
- programowanie mechanizmów gry 
- fabułę gry
- wykonanie części graficznych elementów (rysunki do sekcji opowiadającej historię Mou, tła poziomów, tła do inforacji o poziomach, przeszkody w 1. poziomie)

## Przebieg rozgrywki

### 1) Menu gry
Menu gry jest proste i intuicyjne. Zadbaliśmy, by na pierwszym panelu znajdowały się tylko trzy podstawowe przyciski umożliwiające przejście dalej, zmianę ustawień lub wyjście.
W ustawieniach można zmienić opcje dźwięku. Istnieje opcja wyłączenia/włączenia muzyki oraz efektów dźwiękowych. Za poziom głośności obu tych elementów odpowiadają suwaki.
Dodatkowo poniżej znajduje się opcja resetu gry, jeśli gracz chce przywrócić ustawienia domyślne całej rozgrywki. Powoduje to między innymi wyzerowanie wyników i zablokowanie kolejnych poziomów.

Po wybraniu startu gry i po obejrzeniu krótkiej historii o Mou, ukazuje się kolejna część menu gry. Znajdują się tam trzy poziomy gry, informacje o najlepszych wynikach oraz o odblokowanych poziomach (ikony z dmuchawcami). Dodatkowe informacje o każdym poziomie pojawiają się po kliknięciu na niebieską ikonę z literą “i”. 
Po odblokowaniu wszystkich poziomów pojawia się przycisk “Pokaż zakończenie historii”.

![screen1](/Screens/menu.jpg)
![screen2](/Screens/menu2.jpg)
![screen3](/Screens/menuLvl.jpg)
![screen4](/Screens/menuLvl2.jpg)

### 2) Informacje o poziomach
Przy każdym poziomie w menu można wybrać niebieski znak informacji. Wtedy pokazuje się grafika z tekstem nawiązującym do fabuły gry oraz mówiący, jak przejść dany poziom.

![screen5](/Screens/info1.jpg)
![screen6](/Screens/info2.jpg)
![screen7](/Screens/info3.jpg)

### 3) Poziom I
Rozgrywka 1-szego poziomu jest dosyć prosta. Nasz główny bohater przesuwa się w prawo z coraz to większą prędkością, a naszym zadaniem jest przeskakiwanie pojawiających się przeszkód. 
Skakanie odbywa się za pomocą dotknięcia ekranu, a podwójny skok wykonujemy dotykając ekranu dwukrotnie. Na danym etapie (jeżeli nie został wcześniej zebrany) pojawia się dmuchawiec, który odblokowuje kolejny poziom. Jeżeli nie uda nam się przeskoczyć przeszkody gra się kończy.

![screen8](/Screens/lvl1.jpg)
![screen9](/Screens/lvl1end.jpg)

### 4) Poziom II
Drugi poziom mieści się na bagnach, gdzie rozgrywka opiera się na uwalnianiu świetlików z bąbli, jednocześnie unikając toksyn. Bańki pękamy poprzez kliknięcie w obrazek.
Bańki lecą w górę i wraz z upływem czasu ich prędkość pojawiania się i ruchu rośnie. 
Zwykłe świetliki dają nam 1 punkt, a super świetliki dają nam 3 punkty po ich uwolnieniu. Kliknięcie w toksynę odejmuje nam jedno z trzech żyć. Czasem pojawiają się też bańki z ślimakiem, który po uwolnieniu zmniejsza prędkość baniek. 

![screen10](/Screens/lvl2.jpg)

### 5) Poziom III
Trzeci poziom polega na zbudowaniu jak największej wieży z trójkolorowych bloków, które daje nam gra. Zadanie jest o tyle trudne, że trzeba je ułożyć na platformie, która cyklicznie porusza się od prawej do lewej. Jednak co określony czas platforma może na chwilę przyspieszyć utrudniając zadanie celnego trafienia na platformę, a później na blok. Blok upuszczamy klikając na niego, a każde spudłowanie odejmuje nam jedno z trzech żyć. Po utracie wszystkich żyć rozgrywka się kończy.

![screen11](/Screens/lvl3.jpg)
![screen12](/Screens/lvl3_2.jpg)
![screen13](/Screens/lvl3_3.JPG)

### 6) Historia gry
#### Pierwsza część
Pierwsza część historii Mou pojawia się zaraz po wciśnięciu przycisku start z menu głównego. Ma ona za zadanie wprowadzić gracza w świat gry i pomóc mu zrozumieć dlaczego przemierza świat i jaki jest jego cel.

![screen14](/Screens/story1.jpg)
![screen15](/Screens/story2.jpg)
![screen16](/Screens/story3.jpg)
![screen17](/Screens/story4.jpg)

#### Druga część
Finalna część historii Mou pojawia się po zebraniu 3. dmuchawca podczas gry na 3. poziomie. Wtedy dowiadujemy się, jak kończy się podróż tytułowego bohatera.

![screen18](/Screens/story5.jpg)
![screen19](/Screens/story6.jpg)
![screen20](/Screens/story7.jpg)

### Dodatkowe uwagi
* Do każdej sceny gry dobrana jest muzyka budująca nastrój gry.
* W każdym poziomie występuje efekty cząsteczkowe (Particle System).
* Kolejne poziomy są odblokowywane dopiero po zebraniu Dmuchawca.
* Dane gry (m.in. wyniki) są zapisywane poprzez PlayerPrefs.
