# Instruktioner för kodtest, frontend
##### Läs hela detta dokument innan du börjar koda.

Detta kodtest innehåller en HTML-fil och en JS-fil. HTML-filen innehåller ett formulär där en användare kan fylla i lite information om sig själv, för att sedan beräkna vilken lön de kommer få efter skatt. Öppna HTML-filen i en browser för att se gränssnittet.

Din uppgift är att implementera “Beräkna slutlön”-knappen. D.v.s. att skriva den kod i JS-filen som krävs för att räkna ut vad ens lön blir efter skatt, samt visa denna siffra på sidan när man tryckt på knappen “Beräkna”. Du ser i HTML-filen var du bör rendera denna information.

## Villkor för uträkning

##### Grundlön, brutto
- Utvecklare: 30 000 kr
- Lärare: 27 000 kr
- Kassabiträde: 25 000 kr

##### Antal års erfarenhet
- 0-3 års erfarenhet ger ingen löneökning
- 4-7 års erfarenhet ger en löneökning på 20%
- 8-10 års erfarenhet ger en löneökning på 40%
- 11+ års erfarenhet ger en löneökning på 60%

##### Grundskattesats per ort
Grundskattesatsen baseras på ort och inkomstår:
- Stockholm
-- Inkomstår 2016: 30%
-- Inkomstår 2017: 29%
- Göteborg
-- Inkomstår 2016: 25%
-- Inkomstår 2017: 22%

##### Höginkomsttagarskatt
Tjänar man mellan 36 000 - 45 000 kr betalar man även 50% skatt på all lön mellan 36 000 - 45 000 kr
Tjänar man mer än 45 000 kr betalar man även 50% skatt på all lön mellan 36 000 - 45 000 kr samt 70% skatt på allt över 45 000 kr

## Krav
- Du får endast använda javascript för detta test. Inga ramverk, bibliotek eller dylikt.
- Du behöver inte validera formuläret
- Du behöver inte läga nån tid på styling/css 

## Följande är vad vi kommer fästa uppmärksamhet på
- Läsbarhet
- Möjlighet att utöka koden
- Separation of concerns
- Testbarhet
