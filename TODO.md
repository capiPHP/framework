## DOCS
+ [DB](docs/DB.md)
+ [LIBRARIES](docs/LIB.md)
+ [VERSIONING](docs/VERSIONING.md)
+ [ROUTING](docs/ROUTING.md)


## Lista pytań


+ Jakie funkcjonalności w pierwszej wersji

     Myśle ,że w głównej wersji 1 powinniśmy się skupić na zbudowaniu jakiegoś mechanizmu pracy z bazą danych ,ale takiego nie 
     ograniczajacego. Jakiś podstawowy Routing.


+ plan: terminy, ramy, ograniczenia
     w jakim kierunku idziemy, co i kiedy chcemy osiągnąć
     
     Uważam ,że w życiu trzeba mierzyć wysoko więc proponuje budowe micro-frameworka dla api / rest-api
     
     Sądze ,że najważniejsze to teraz się skupić na budowie dobrego routingu , który będzie ułatwiać prace ani utrudniać. Dla przydładu
     śiągnołem sobie Lumen framework dla api. No przyznam ,że funkcjonowanie routingu jest dobra acz kolwieg nie powala na kolana.
     
     Drugim to praca z bazą danych. 


+ jakie pierwsze potrzeby chcemy zaspokoić tym kodem?

    moje oczekiwania są takie, by móc korzystać z jakiegoś przemyślanego rozwiązania,
    aby nie było potrzebne tworzenie kodu na nowo.
    Mam na myśli, np stanaryzowane pola, obiekty do wykorzystania, ktore w zasadzie istnieja w innych moich projektach   
    Value
    Name
    Collection
    
    TO od strony modelu danych, być może to będzie bezpośrednio związane z wymianą danych, dlatego myślę, że 
    requesty do bazy danych czy requesty do API można traktować tak samo
    konfiguracja powinna być jednakowa, tzn host, auth, itd
    
    Dane w zasadzie sa zalezne od typu a nie od zrodła, przykład:
    
    
    config.yaml
    
        source:
            -
                name: db
                auth: 
                    type: plain
                    user: admin
                    pass: admin
            -
                name: github
                auth: 
                    type: token
                    user: tomasz
                    token: KJHSFJKDKJFHJKHKJSHJKDAHKJFHKJHKJDHAJKDFLH                    
    
     
    

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

