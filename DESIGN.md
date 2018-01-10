# Programmeerproject - Design

![Design](https://i.imgur.com/s0mLxN1.png)

### Plugins & API's

#### API:
- https://www.tvmaze.com/api

#### Plugins
- MessageUI

### Utility Models

#### Classes & Structs:
- Tv Serie Struct
- Gebruiker Struct

#### Functions:
- Series ophalen van tvmaze API
- Haal de favorieten van een gebruiker op uit de Firebase
- Haal de vrienden van een gebruiker op uit de Firebase
- Login
- Create Account
- Voeg een serie toe aan favorieten
- Voeg een vriend toe
- Verstuur een uitnodiging naar een vriend

### Data
De informatie over de gebruiker wordt opgeslagen in Firebase. De gebruiker moet minstens een naam en emailadres opgeven en kan inloggen met een email adres en een wachtwoord. In de database moet ook per gebruiker worden opgeslagen wanneer een gebruiker een vriend toevoegt aan zijn vriendenlijst en wanneer een gebruiker een film opslaat in de watchlist. Het opgeslagen emailadres wordt ook gebruikt om uitnodigingen te ontvangen. 

De informatie over series wordt opgehaald van de API van tvmaze in JSON formaat. Bij deze API kan ook gebruik gemaakt worden van een zoek functie voor het zoeken van series in hun database. Uit een query komt wel veel informatie over de serie, wat niet allemaal nuttige informatie is voor mijn app. Ik zal dus niet alles ophalen.
