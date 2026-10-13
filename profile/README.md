![header](/imagesrc/ZinBanner.png "template_header")
# Welkom

Dit is de GitHub-pagina van **iStandaarden**. Hier vindt u onder andere de technische specificaties voor het **Netwerkmodel**, wat op dit moment voor de **iStandaard iWlz** in ontwikkeling is en project-views voor de wijzigingsverzoeken en bevindingen van een iStandaard. 

# Actuele releases en lopende wijzigingen

De actuele status van de wijzigingsverzoeken en bevindingen voor de iWlz of iPgb kunt u hier vinden:

- Wijzigingsverzoeken en bevindingen iPgb: [Overzicht iPgb](https://github.com/orgs/iStandaarden/projects/12)
- Wijzigingsverzoeken, Request for Comments en bevindingen iWlz: [Overzicht iWlz](https://github.com/orgs/iStandaarden/projects/9)



# Netwerkmodel iWlz
Het iWlz-netwerkmodel biedt zorgaanbieders, zorgkantoren en andere partijen die actief zijn in de langdurige zorg de mogelijkheid om zorgadministratieve gegevens, die nodig zijn voor de uitvoering van hun taken, direct bij de bron te raadplegen.

De technische specificaties op deze GitHub-pagina ondersteunen het **[Informatiemodel iWlz](https://informatiemodel.istandaarden.nl/)** zoals gepubliceerd via **[iStandaarden.nl](https://www.istandaarden.nl/)**. De specificaties hebben betrekking op de totstandkoming en implementatie van het iWlz-netwerkmodel binnen het **Actieprogramma iWlz**.

Meer informatie over het Actieprogramma iWlz vindt u op **[iStandaarden.nl](https://www.istandaarden.nl/)** of direct via:  
https://www.istandaarden.nl/algemeen/map/netwerkmodel

## Documentatie Netwerkmodel iWlz

De overzichtspagina bevat verwijzingen naar de onderstaande 3 publicaties: [Aanvullende documentatie Netwerkmodel iWlz](https://istandaarden.github.io/current/)

### Het Afsprakenstelsel iWlz-netwerkmodel

Het **Afsprakenstelsel iWlz-netwerkmodel** beschrijft de gezamenlijke afspraken, voorwaarden en technische randvoorwaarden die nodig zijn om partijen en systemen binnen het iWlz-netwerkmodel veilig, betrouwbaar en interoperabel met elkaar te laten samenwerken.

In het afsprakenstelsel vindt u onder meer afspraken over identificatie en authenticatie, autorisatie, beveiliging, logging, netwerkvoorzieningen, serviceafspraken, testen, toetreden en beheer. Het afsprakenstelsel vormt daarmee het kader waarbinnen technische implementaties van het iWlz-netwerkmodel worden gerealiseerd.

- [Gepubliceerde versie Afsprakenstelsel iWlz](https://istandaarden.github.io/Afsprakenstelsel-iWlz/)



### Koppelvlakspecificaties

De **koppelvlakspecificaties** beschrijven de concrete technische interfaces waarmee systemen binnen het iWlz-netwerkmodel gegevens met elkaar uitwisselen. Hier vindt u onder andere GraphQL-schema's, voorgeschreven queries, gegevensstructuren, technische interactiepatronen, foutafhandeling en registerspecifieke specificaties.

De koppelvlakspecificaties zijn afzonderlijk opgenomen van de actuele releases, technische uitwerkingen en wijzigingen. De informatie over releases en wijzigingen geeft aan **welke versie, technische uitwerking of wijziging van toepassing is**. De koppelvlakspecificaties beschrijven **hoe de technische interactie met een specifieke voorziening of een specifiek register moet worden geïmplementeerd**.

Voor documentatie over de samenhang tussen de verschillende koppelvlakspecificaties kunt u gebruikmaken van:

- [Koppelvlakspecificatie netwerkmodel](https://istandaarden.github.io/koppelvlakspecificatie-netwerkmodel/)

De volgende koppelvlakspecificaties zijn beschikbaar:

- [iWlz Generiek](https://github.com/iStandaarden/iWlz-generiek) - netwerkbrede en generieke functionaliteit;
- [Indicatieregister](https://github.com/iStandaarden/iWlz-indicatie) - raadplegen van Wlz-indicatiegegevens en cliëntcontactgegevens;
- [Bemiddelingsregister](https://github.com/iStandaarden/iWlz-bemiddeling) - raadplegen van Wlz-bemiddelingsgegevens en cliëntcontactgegevens;
- [Leveringsregister](https://github.com/iStandaarden/iWlz-levering) - raadplegen van Wlz-zorgleveringsgegevens.


## Implementatiehandleiding: hoe sluit ik op het netwerkmodel aan?

De **implementatiehandleiding** ondersteunt softwareleveranciers, ontwikkelaars, architecten en technisch beheerders bij het realiseren van een technische aansluiting op het iWlz-netwerkmodel.

In de implementatiehandleiding vindt u praktische informatie over de voorbereiding en inrichting van een aansluiting, waaronder configuratie, authenticatie en autorisatie, het implementeren van koppelvlakken, testen en het aansluiten op beschikbare omgevingen.

De implementatiehandleiding is aanvullend op de normatieve specificaties. De specificaties beschrijven **wat** een implementatie moet ondersteunen; de implementatiehandleiding helpt bij **hoe** deze aansluiting praktisch kan worden gerealiseerd.

- [Implementatiehandleiding netwerkmodel](https://istandaarden.github.io/implementatiehandleiding-netwerkmodel/)

## Repositories

### Core interfaces

Hier vindt u de repositories met de kerninterfaces van het iWlz-netwerkmodel.

- [iWlz Generiek](https://github.com/iStandaarden/iWlz-generiek)
- [Indicatieregister](https://github.com/iStandaarden/iWlz-indicatie)
- [Bemiddelingsregister](https://github.com/iStandaarden/iWlz-bemiddeling)
- [Leveringsregister](https://github.com/iStandaarden/iWlz-levering)

### Supporting components

Hier vindt u ondersteunende technische onderdelen die bij meerdere interfaces of implementaties worden gebruikt.

- [Afsprakenstelsel iWlz](https://github.com/iStandaarden/Afsprakenstelsel-iWlz)
- [Koppelvlakspecificatie netwerkmodel](https://github.com/iStandaarden/koppelvlakspecificatie-netwerkmodel)
- [Implementatiehandleiding netwerkmodel](https://github.com/iStandaarden/implementatiehandleiding-netwerkmodel)
- [Request for Comments](https://github.com/iStandaarden/iWlz-RequestForComment)
- [Request for Changes](https://github.com/iStandaarden/iWlz_RequestForChange)
- [iWlz Adresboek](https://github.com/iStandaarden/iWlz-adresboek-public)
- [iWlz Codelijsten](https://github.com/iStandaarden/iWlz-codelijsten-APiWlz)

## Contact

Voor vragen over de technische documentatie of de repositories kunt u contact opnemen met:

- **E-mail:** [info@istandaarden.nl](mailto:info@istandaarden.nl)
