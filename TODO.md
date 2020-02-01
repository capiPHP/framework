## Lista pytań

+ jakie biblioteki będą używane, włączane do frameworka?

+ Jakie funkcjonalności w pierwszej wersji

     Myśle ,że w głównej wersji 1 powinniśmy się skupić na zbudowaniu jakiegoś mechanizmu pracy z bazą danych ,ale takiego nie 
     ograniczajacego. Jakiś podstawowy Routing.

+ jak bedziemy wersjonować?

     myśle ,że możemy zacząć od versi 1.0.1
     
     1 - to będzie oznacznie głównego modółu(wersja) czyli jakieś istotne zmiany
     
     0 - to może być pod modół tutaj możemy sobie oznaczać mniejsze zmiany poprawiające stabilnośc frameworka
     
     1 - i ostatni to małe poprawki w kodzie poprawiające jego jakość 
     
     myśle ,że idąc tym tokiem będzie w miare jasno poukładane

+ plan: terminy, ramy, ograniczenia   
     w jakim kierunku idziemy, co i kiedy chcemy osiągnąć
     
     Uważam ,że w życiu trzeba mierzyć wysoko więc proponuje budowe micro-frameworka dla api / rest-api
     
     Sądze ,że najważniejsze to teraz się skupić na budowie dobrego routingu , który będzie ułatwiać prace ani utrudniać. Dla przydładu
     śiągnołem sobie Lumen framework dla api. No przyznam ,że funkcjonowanie routingu jest dobra acz kolwieg nie powala na kolana.
     
     Drugim to praca z bazą danych. I tutaj trzeba by sobie zadać pytanie czy idziemy na gotowca i użyjemy boundle ORM i temat z bazą
     mam w pewnym stopniu załatwiony. Czy ambitnie stworzymy własny system do komunikacji z bazą danych user by tylko tworzył zapytania 
     w sql. Uważam ,że drugie podejście jest lepsze bo szybciej będzie działać framwework. Lecz znów przy dużych projektach będzie 
     troche nie wygodnie.

jakie pierwsze potrzeby chcemy zaspokoić tym kodem?

## Lista zadań
+ docker
    + plik konfiguracyjyny
    + docer hub repo

+ composer
    + plik oknfiguracyjny dla biblioteki/framweorka
        composer.json
    + zrodlo na 
        https://getcomposer.org/doc/
        
    + publikacja na 
        https://packagist.org/

