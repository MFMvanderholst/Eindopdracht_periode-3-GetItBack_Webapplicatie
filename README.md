# Eindopdracht_periode-3-GetItBack_Webapplicatie
Les frameworks, bij het school MBO Utrecht is dit een eindopdracht voor periode 3


## Deadline
**Inleverdatum:** 5 apr om 23:59

## Afspraken

1. Maak gebruik van branches, ook al is het voor een opdracht.
2. Maak van elk afgemaakte functie of styling een commit met wat je hebt gemaakt.
3. Maak gebruik van commentaar in je code zodat het georganiseerd en gestructureerd is.
4. Maak nette code.
5. Probeer zoveel mogelijk in de les te maken.
6. Je kan het!!

## Voorwaarden

### Ontwikkelingsstappen:

1. Opzetten van de Laravel-omgeving en installeren van Laravel Breeze voor authenticatie.
2. Aanmaken van de nodige databasetabellen (gebruikers, ritten, instellingen).
3. Ontwikkelen van de gebruikersinterface met Tailwind CSS en integreren van Livewire-componenten.
4. Implementatie van de ritboekingsfunctionaliteit, inclusief integratie met de Google Distance Matrix API.
5. Opzetten van het admin-dashboard en mogelijk maken van kilometerprijsconfiguratie.
6. Ontwikkelen van de factureringsfunctionaliteit en het ritoverzicht voor gebruikers.
7. Testen van de applicatie op functionaliteit, beveiliging en responsiviteit.
8. Documenteren van de code en schrijven van gebruiksaanwijzingen voor eindgebruikers en beheerders. (Mag in de code comments)

### Leverables:

- Volledige broncode van de applicatie.
- Documentatie voor het opzetten en configureren van de applicatie.

**Opmerking:** Zorg ervoor dat alle persoonlijke en gevoelige informatie beveiligd is volgens de beste praktijken voor webbeveiliging. Test de applicatie grondig om ervoor te zorgen dat er geen beveiligingslekken zijn.


## Functionaliteiten:

1. Gebruikersauthenticatie en -registratie:
    - Implementeer gebruikersauthenticatie met Laravel Breeze.
    - Bied functionaliteit voor gebruikersregistratie, inloggen, wachtwoordherstel en e-mailverificatie.

2. Dashboard:
    - Na inloggen krijgt de gebruiker toegang tot het dashboard.
    - De gebruiker kan zijn bedrijfsgegevens invullen op zijn profiel pagina. (Velden: bedrijfsnaam, Straat en huisnummer,  - postcode, Plaats, Land, KVKnummer, Telefoonnummer
    - Het dashboard biedt een overzicht van alle uitgevoerde, lopende en geplande ritten.

3. Ritboeking:
    - Sta toe dat gebruikers een nieuwe rit boeken door zowel het ophaal- als afleveradres op te geven.
    - Integreer de Google Distance Matrix API om de afstand tussen het ophaal- en afleveradres te berekenen en sla dit op.
    - Bereken de kosten van de rit op basis van de afstand en de per kilometer ingestelde prijs door de admin en sla dit op.

4. Admin Dashboard:
    - Ontwikkel een apart dashboard voor admin.
    - Stel admin in staat om de kilometerprijs in te stellen en te wijzigen in een opties tabel.
    - Geef admins de mogelijkheid om alle gebruikersritten te bekijken en te beheren. (Kan status van ritten aanpassen - In afwachting, onderweg, afgerond)

5. Facturering en Overzicht:
    - Laat gebruikers hun ritgeschiedenis en bijbehorende kosten bekijken.
    - Genereer facturen op basis van voltooide ritten en de berekende afstandskosten.
    - Implementeer een functie voor gebruikers om hun facturen te downloaden of per e-mail te ontvangen.

6. Styling en Responsiviteit:
    - Gebruik Tailwind CSS voor de styling van de applicatie.
    - Zorg ervoor dat de applicatie responsive is en goed werkt op zowel desktop- als mobiele apparaten.


## User Stories

### Voor Gebruikers:
1. Als een nieuwe gebruiker wil ik mij kunnen registreren, zodat ik toegang kan krijgen tot de GetItBack diensten.

+ Acceptatiecriteria:
  - Gebruiker kan een registratieformulier invullen met persoonlijke informatie.
  - Gebruiker ontvangt een bevestigingsmail na registratie.
  - Gebruiker kan zijn e-mailadres verifiëren om de registratie te voltooien.

2. Als gebruiker wil ik kunnen inloggen, zodat ik toegang heb tot mijn persoonlijke dashboard.

+ Acceptatiecriteria:
  - Gebruiker kan inloggen met e-mailadres en wachtwoord.
  - Bij succesvolle authenticatie wordt de gebruiker doorgestuurd naar zijn dashboard.

3. Als gebruiker wil ik een nieuwe rit kunnen boeken, zodat mijn pakket van de ene naar de andere locatie wordt vervoerd.

+ Acceptatiecriteria:
  - Gebruiker kan ophaal- en afleveradressen invoeren.
  - Gebruiker ziet de geschatte kosten op basis van afstand en kilometerprijs.
  - Gebruiker kan de boeking bevestigen en een overzicht van de rit zien.

4. Als gebruiker wil ik mijn ritgeschiedenis kunnen bekijken, zodat ik een overzicht heb van mijn eerdere activiteiten.

+ Acceptatiecriteria:
  - Gebruiker kan een lijst van eerdere ritten zien met details zoals datums, adressen en kosten.
  - Gebruiker kan de details van elke rit bekijken voor meer informatie.

5. Als gebruiker wil ik facturen kunnen downloaden of ontvangen via e-mail, zodat ik mijn uitgaven kan bijhouden.

+ Acceptatiecriteria:
  - Gebruiker kan facturen voor voltooide ritten downloaden vanuit het dashboard.
  - Gebruiker kan opties selecteren om facturen via e-mail te ontvangen.


### Voor Admins:
1. Als admin wil ik de kilometerprijs kunnen instellen en aanpassen, zodat ik de tarieven van de dienst kan beheren.

+ Acceptatiecriteria:
  - Admin kan de huidige kilometerprijs bekijken en bewerken.
  - De nieuwe kilometerprijs wordt onmiddellijk toegepast op nieuwe ritten.

2. Als admin wil ik alle geboekte ritten kunnen bekijken, zodat ik een overzicht heb van de lopende en voltooide leveringen.

+ Acceptatiecriteria:
  - Admin kan een lijst van alle ritten bekijken met relevante details.
  - Admin kan zoeken en filteren binnen de ritgegevens.

3. Als admin wil ik gebruikersaccounts kunnen beheren, zodat ik kan zorgen voor een veilige en betrouwbare gebruikersbasis.

+ Acceptatiecriteria:
  - Admin kan gebruikersaccounts activeren, deactiveren of verwijderen.
  - Admin kan de registratiegegevens van gebruikers bekijken en bewerken.



## Voortgang

Project map gemaakt met het framework laravel
Branches gemaakt volgens git worktree