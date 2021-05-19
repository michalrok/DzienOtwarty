# DzienOtwarty
Aplikacja powstała na spotkanie z administratorami Teams w polskich szkołach. Chciałem pokazać, jak Power Apps + Power Automate mogą się przydać w edukacji. Jako, że był to koniec roku szkolnego, czas spotkań indywidualnych uczniów i rodziców z nauczycielami, to wybór był prosty - zrobiłem apkę do organizacji takich spotkań.

## Jak to działa
Zakładasz spotkanie (np. Dni Otwarte Maj 2021). Wprowadzasz listę nauczycieli, dla każdego podajesz datę+godziny kiedy może się spotkać. Określasz czas trwania jednego spotkania, np. 15 minut. Uczniowie i rodzice widzą w Teams listę wolnych terminów u każdego z nauczycieli, mogą wybrać taki, jaki im odpowiada. Program zakłada spotkania w Teams i pilnuje, aby dwie osoby nie wpisały się na to samo spotkanie.

## Instalacja
1. Teams, otwieramy po lewej stronie "..." i szukamy aplikacji Power Apps
2. Naciskamy "Zacznij teraz"
3. Wybieramy zespół, w którym będzie dostępna aplikacja (patrz Uwagi niżej)
4. Kiedy dostaniemy powiadomienie, że Power Apps są już dostępne w naszym zespole (chwilę to trwa), otworzy się ekran Power Apps - tu można stworzyć swoją aplikację. Nie robimy tego - idziemy na stronę https://emea.flow.microsoft.com
5. Logujemy się (link w prawym górnym)
6. Z listy środowisk w prawym górnym rogu wybierz nazwę swojego zespołu z pkt. 3
7. W menu po lewej wybieramy Rozwiązania
8. Na pasku wybieramy Importuj i ładujemy plik pobrany z tej strony (DzienOtwarty_1_0_0_x.zip)
9. Czekamy kilka minut, aż się pojawi Dzień Otwarty na liście rozwiązań
10. Kiedy pojawi się lista połączeń, zakładamy kolejno Teams/Outylook/Dataverse
11. Wracamy do Teams i aplikacji Power Apps z punktu 4, przełączamy na stronę główną
12. Na liście ostatnio używanych aplikacji znajdujemy kolejno:
* Nauczyciele - otwieramy i przyciskiem po prawej u góry "Opublikuj w Teams" udostępniamy w kanale prywatnym w naszym zespole (patrz Uwagi poniżej)
* Spotkania - jw.
* Zapisane osoby - jw.
* Zapisy na konsultacje - tą jedną aplikację udostępniamy WSZYSTKIM w zespole, aby mogli się zapisywać

## Jak używać?
* idziemy do naszego wybranego zespołu i widzimy nowe zakładki z poszczególnymi apkami
* w aplikacji Spotkania dodajemy nazwę naszego spotkania (np. Dzień Otwarty dla klas 7-8)
* w aplikacji Nauczyciele wprowadzamy listę osób, z którymi się można spotkać, godziny tych spotkań i czas trwania jednego
* kiedy na ekranie spotkania zaznaczymy, że jest już otwarte do zapisów, to w "Zapisane osoby" zobaczymy terminy poszczególnych spotkań
* uczniowie, albo rodzice przez ich konta, używają zakładki "Zapisy na konsultacje" aby wybrać dogodny dla siebie termin
* spotkanie można anulować w tej samej zakładce, w której się zapisujemy
* spotkania pojawiają się w kalendarzu Teams u ucznia i u nauczyciela

## Uwagi i typowe kłopoty
* zespół, w którym instalujesz aplikację musi być typu "Inne" (chodzi o ten ekran, kiedy zakładając zespół wybierasz Zajęcia/Personel/Inne)
* do zespołu musi mieć wgląd każdy, kto ma móc się zapisać; jeśli więc nie masz gotowego zespołu np. na klasy 1-3, to zrób zespół Publiczny
* aplikacje do wprowadzania danych spotkań/nauczycieli (czyli wszystkie oprócz "Zapisy na konsultacje") można dodać do prywatnego kanału w zespole - nie muszą ich widzieć uczniowie
* 
