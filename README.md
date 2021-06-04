# DzienOtwarty
Aplikacja powstała na spotkanie z administratorami Teams w polskich szkołach. Chciałem pokazać, jak Power Apps + Power Automate mogą się przydać w edukacji. Jako, że był to koniec roku szkolnego, czas spotkań indywidualnych uczniów i rodziców z nauczycielami, to wybór był prosty - zrobiłem apkę do organizacji takich spotkań.

## Jak to działa
Zakładasz spotkanie (np. Dni Otwarte Maj 2021). Wprowadzasz listę nauczycieli, dla każdego podajesz datę+godziny kiedy może się spotkać. Określasz czas trwania jednego spotkania, np. 15 minut. Uczniowie i rodzice widzą w Teams listę wolnych terminów u każdego z nauczycieli, mogą wybrać taki, jaki im odpowiada. Program zakłada spotkania w Teams i pilnuje, aby dwie osoby nie wpisały się na to samo spotkanie.

## Instalacja
Instrukcja wideo: https://www.youtube.com/watch?v=C6WpAXg_eCw

1. Teams, otwieramy po lewej stronie "..." i szukamy aplikacji Power Apps
2. Naciskamy "Zacznij teraz"
3. Wybieramy zespół, w którym będzie dostępna aplikacja (patrz Uwagi niżej)
4. Kiedy dostaniemy powiadomienie, że Power Apps są już dostępne w naszym zespole (chwilę to trwa), otworzy się ekran Power Apps - tu można stworzyć swoją aplikację. Nie robimy tego - idziemy na stronę https://emea.flow.microsoft.com
5. Logujemy się (link w prawym górnym)
6. Z listy środowisk w prawym górnym rogu wybierz nazwę swojego zespołu z pkt. 3
7. W menu po lewej wybieramy Rozwiązania
8. Na pasku wybieramy Importuj i ładujemy plik pobrany z tej strony (DzienOtwarty.zip)
9. Czekamy kilka minut, aż się pojawi Dzień Otwarty na liście rozwiązań
10. Kiedy pojawi się lista połączeń, zakładamy kolejno Teams/Outylook/Dataverse
11. Wracamy do Teams, przełączamy na stronę naszego zespołu z pkt. 3
12. Zakładamy "tajny" kanał wewnątrz zespołu dla osób, które będą miały wgląd w listę nauczycieli i ich plan spotkań
13. Teraz dodajemy wszystkie cztery apki do kanałów naszego zespołu. W tym celu otwieramy apkę (Teams -> Power Apps -> Tworzenie -> Zainstalowane aplikacje -> Dzień Otwarty -> Zobacz wszystkie -> Aplikacje -> tu wybieramy jedną z apek i klikamy na nią aby otworzył się edytor). W edytorze w prawym górnym rogu jest przycisk Opublikuj w aplikacji Teams. Po wciśnięciu Dalej wskazujemy do którego kanału dodać apkę - "jawnego" czy "tajnego".
14. Do "tajnego" (tego dla nauczycieli/administratora) kanału dodajemy (+) kartę Power Apps - wśród aplikacj znajdujemy kolejno: Spotkania, Nauczyciele, Zapisane osoby
15. Do "jawnego" (tego dla uczniów i rodziców) kanału dodajemy (+) kartę Power Apps - Zapisy na konsultacje (możemy zmienić nazwę karty wedle potrzeb)

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
* jeśli apka pojawiła się w odpowiedniej zakładce ale nie działa, np. nie generują się terminy spotkań: otwórz listę składników rozwiązania (pkt. 13 instrukcji wyżej), tylko zamiast aplikacji zobacz przepływy. Klikając w "..." przy każdym z nich sprawdź, czy jest włączony (wtedy w menu jest opcja Wyłącz) czy też wyłączony (w menu opcja Włącz). Wszystkie 4 przepływy powinny być włączone.  
