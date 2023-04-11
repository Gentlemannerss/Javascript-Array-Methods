# Opdracht beschrijving

Deze opdracht bestaat uit meerdere opdrachtjes om met array methoden te kunnen oefenen. Om de opdracht te maken kun je de opdracht clonen of downloaden naar jouw eigen computer. De uitwerkingen staan op de branch _uitwerkingen_.

Dit project bevat de volgende bestanden:

1. `arrayMethods.js`

## Script runnen
Als je de code wil runnen kun je dit doen door het volgende in de terminal in te voeren:

`nodemon arrayMethods.js`

Als je wisselt van bestand moet je nodemon eerst stoppen (ctrl + c voor zowel Windows als Mac) en dan opnieuw starten met de nieuwe bestandsnaam, zoals bijvoorbeeld:

`nodemon methods.js`

.map
Om een nieuwe array te maken (maar van alle object entry's uit die array)
.filter
kan zoeken en meerdere antwoorden vinden
.find
zoekt naar het eerste item wat over een komt
.sort
Je wilt de volegorde aanpassen op waarde van een conditie

callback van .map
.map returnt de input waar de callback functie op is uitevoerd
callback van .filter
returned meerdere true of false
.find
returned een true, en stopt de loop.
.sort
returend een 1, 0 of -1

methode van .map
Je maakt een nieuwe array aan waarvoor elke index van de oudere array een nieuwe index wordt gemaakt waarop de callback funcite is uitgevoerd.
methode van .filter
zoeken in de orginele array naar de waarde die overeenkomt met de opgegeven waarde en returned dit
methode van .find
zoekt in de orginele array naar de eerste waarde die overeenkomt.
methode van .sort
past de volegorde aan van de originele array.

.map
output is gelijk aan input
.filter
output is minder dan input, als de conditie overal hetzelfde is kan je wel gelijk aan gelijk zijn.
.find
output is minder dan input
.sort
output is gelijk aan input.

.map
nieuwe array aangemaakt
.filter
nieuwe array aangemaakt, ook als er niks gevonden wordt, wordt er een array gemaakt.
.find
nieuwe array aangemaakt, ook als er niks gevonden wordt, wordt er een array gemaakt.
.sort
orginele array wordt de volegorde aangepast.