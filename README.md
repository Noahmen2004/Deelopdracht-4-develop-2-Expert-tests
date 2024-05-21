# Expert Tests

*Projectteam: Noah Menschaert; luca Poppe*

*Datum 22/1/2024*

## De testen
De testen werden uitgevoerd op 2 personen Kai Cherchyd en Warre De Vriendt We hebben 3 verschillende protoypes van een centraal touchscreen (dat functioneert als bedieningspaneel voor de auto) uitgetest op hun. 
We hebben telkens 1 bedieningspaneel voor hun gezet. In de eerste fase van de test voerden ze een opdracht uit wanneer de auto zogezegd stilstaat. In de tweede fase deden ze dit terwijl de auto zogezegd in beweging is. Hierbij zal er altijd een functie zijn die ervoor zorgt dat het bedieningspaneel niet meer te gebruiken is door de chauffeur.  
De bedoeling is dat ze de opdrachten uitvoeren en vertellen wat makkelijk of moeilijk is en mogelijke opmerkingen waar je ze kan denken. Daarna moeten ze elk protype beoordelen op basis van de tien heuristieken van Nilsen.

#### De opdrachten die ze moesten uitvoeren per prototype:
- Ga naar playlist <naam> en leg het derde nummer op.
- Plan een route naar <bestemming> via google maps.
- Doe berichten open en lees het laatste bericht in de derde chat luidop voor.
- Ga naar telefoon en bel <nummer>.
- Zet de kaart in een andere instelling.

## Evaluatie door middel van de 10 heuristieken van Nielsen 

#### <u>Warre De Vriendt:<u/>

Prototype 1 draaiende interfaces:

<p>
  <img src="https://github.com/Noahmen2004/Deelopdracht-4-develop-2-Expert-tests/blob/main/Screenshot%202024-05-21%20120050.png" width="500" 
     height="auto" />

</p>

Prototype 2 polarisatie interface:

<p>
  <img src="https://github.com/Noahmen2004/Deelopdracht-4-develop-2-Expert-tests/blob/main/Screenshot%202024-05-21%20120103.png" width="500" 
     height="auto" />

</p>


Prototype 3  schuivende interface:

<p>
  <img src="https://github.com/Noahmen2004/Deelopdracht-4-develop-2-Expert-tests/blob/main/Screenshot%202024-05-21%20120119.png" width="500" 
     height="auto" />

</p>

#### <u>Kai Cerchyd:<u/>

Prototype 1 draaiende interfaces:

<p>
  <img src="https://github.com/Noahmen2004/Deelopdracht-4-develop-2-Expert-tests/blob/main/Screenshot%202024-05-21%20120119.png" width="500" 
     height="auto" />

</p>


Prototype 2 polarisatie interface:

<p>
  <img src="https://github.com/Noahmen2004/Deelopdracht-4-develop-2-Expert-tests/blob/main/Screenshot%202024-05-21%20120136.png" width="500" 
     height="auto" />

</p>


Prototype 3  schuivende interface:

<p>
  <img src="https://github.com/Noahmen2004/Deelopdracht-4-develop-2-Expert-tests/blob/main/Screenshot%202024-05-21%20120149.png" width="500" 
     height="auto" />

</p>

## Samenvatting

Beide geïnterviewden geven de voorkeur aan de polarisatie-interface omdat deze het eenvoudigst en meest intuïtief is. De schuivende interface wordt gezien als een beter alternatief dan het draaiende scherm vanwege de verminderde afleiding voor de bestuurder. Dit omadat het makkelijker is om foutief toch naar de draaiende interface te kijken (want deze blijft centraal staan) dan bij de schuivende interface(waar de interface weg van de chauffeur schuift).  Er zijn zorgen over de zichtbaarheid en documentatie bij de schuivende interface en suggesties voor foutpreventie bij alle prototypes.

## Designrequirements

#### Zijdelingse Verplaatsing:
- Het scherm moet volledig buiten het gezichtsveld van de bestuurder kunnen verschuiven wanneer de auto in beweging is, zodat afleiding geminimaliseerd wordt.

#### Foutenherkenning en -herstel:
- Ingebouwde mechanismen voor het herkennen en herstellen van fouten, zoals pop-up meldingen of geluidssignalen wanneer de bestuurder probeert het scherm te gebruiken tijdens het rijden.
  
#### Minimalistisch Design:
- Vermijd overmatige visuele elementen en houd de interface strak en overzichtelijk om afleiding te minimaliseren.

#### Error Prevention:
- Zorg voor error prevention door eventueel een melding te geven als je toch naar het centraal touchscreen probeert te kijken.
  
## Ontwerpbeslissingen

#### Keuze van Interface Type:
- Polarisatie Interface: Wordt sterk aanbevolen vanwege de eenvoud en intuïtiviteit, en vermindert de kans dat de bestuurder probeert het scherm te bekijken.

#### Gebruikersfeedback en Interactie:
- Eenvoudige Bedienbaarheid: De interface moet gebruiksvriendelijk zijn en ontworpen voor snel en intuïtief gebruik zonder uitgebreide training.
- Foutenherkenning en -herstel: Ingebouwde mechanismen voor het herkennen en herstellen van fouten, zoals pop-up meldingen of geluidssignalen wanneer de bestuurder probeert het scherm te 
  gebruiken tijdens het rijden.

#### Documentatie en Help Functie:
- Help en Documentatie: Zorg voor duidelijke documentatie en een gemakkelijk toegankelijke helpfunctie binnen de interface voor het geval er iets misgaat


