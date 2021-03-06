# ProgrammeerProject - Rosalie Snijders

## Probleem
De laatste aantal jaren wordt het steeds makkelijker om online televisie series te kijken of terug te kijken. Veel vrienden kijken dan ook vaak dezelfde series maar dat niet van elkaar weten, hierdoor kijken ze vaak die series alleen. 

De oplossing voor dit probleem wordt een app waarin je aan kan geven welke series je volgt, wanneer de volgende aflevering uitkomt van die serie. In de app kan je dan kijken naar welke series je vrienden kijken en ze uitnodigen om het samen te kijken. Als ze eenmaal hebben aangegeven dat ze samen een serie kijken kunnen ze samen een datum prikken om de aflevering te gaan kijken. De doelgroep van deze applicatie bestaat uit mensen die graag series samen kijken en graag up to date blijven van de huidige series op tv en op internet. Door deze app onstaat er meer menselijk contact en kan het kijken van series minder eenzaam worden. De leukste functie van de app wordt dan ook dat je van elkaar kan bijhouden waar je bent bij een serie en het sturen van uitnodigingen. 

Er bestaan al redelijk wat apps waarin je kan bijhouden welke series je volgt en wanneer je de volgende afleveringen van die serie uitkomen, zoals bijvoorbeeld de apps Serist en TV Time. Ik kan deze apps gebruiken om de layout en sommige functionaliteiten van mijn app te inspireren.  Zover ik weet kan je echter bij die apps nog niet zien wat je vrienden kijken en ze uitnodigingen sturen. Dit wordt dan ook de grootste uitdaging van mijn app. Hiervoor ga ik waarschijnlijk MessageUI gebruiken om uitnodigingen te versturen. Dit is een framework die de gebruiker smsjes en email laat versturen zonder de app te verlaten. Hierbij kan je van tevoren aangeven wie de ontvanger is en wat er in het bericht staat. De gebruiker zou dan alleen op verzenden moeten drukken. Daarnaast ga ik Firebase gebruiken om de gebruikers te laten inloggen en informatie van andere gebruikers te laten zien.

Databronnen:
- tvmaze API: https://www.tvmaze.com/api

Externe componenten:
- Firebase Database
- Firebase Auth
- MessageUI

Overeenkomende apps:
- Serist
- TV Time
- Next Episode
- TVShow Time
- SeriesGuide

## Features

- Account maken/inloggen
- Informatie over televisie series vinden
- Zien wanneer de volgende aflevering van een serie wordt uitgezonden
- Bijhouden welke series de gebruiker volgt
- Andere gebruikers van de app vinden
- Andere gebruikers toevoegen als vriend
- Informatie over andere gebruikers kunnen zien
- Uitnodigingen sturen naar vrienden om samen een serie te kijken

## Minimum Viable Product/Optional

De gebruiker moet in het eindproduct op zijn minst Series kunnen toevoegen aan een watchlist en kunnen zien wanneer de volgende aflevering van die serie uitkomt. Daarnaast moet de gebruiker ook informatie over de serie kunnen bekijken. De gebruiker moet ook vrienden kunnen toevoegen en die vrienden een uitnodiging kunnen sturen om samen een serie te kijken. Al deze informatie moet opgeslagen worden in een database. Het zou fijn zijn als er een uitnodiging wordt verstuurd er dan al een  gegenereerd bericht staat, zodat de gebruiker zelf niet een bericht hoeft te typen en alleen op verzenden hoeft te drukken. 

Een optionele functie van de app wordt dat als de gebruiker een uitnodiging stuurt dat er meteen een datumprikker agenda wordt meegestuurd, zodat ze meteen een datum kunnen prikken om samen de serie te kijken.


## Schets

![Schets](https://i.imgur.com/s0mLxN1.png)
