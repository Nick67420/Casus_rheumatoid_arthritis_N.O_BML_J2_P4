# Beheer van het onderzoek met GitHub
## Inleiding


Tijdens dit transcriptomicsproject naar reumatoïde artritis (RA) is GitHub gebruikt om de onderzoeksbestanden te organiseren, te documenteren en beschikbaar te maken. GitHub biedt daarnaast mogelijkheden voor versiebeheer, waardoor wijzigingen in scripts, resultaten en documentatie kunnen worden bijgehouden.

Door de verschillende onderdelen van het onderzoek centraal te verzamelen, wordt de uitgevoerde workflow overzichtelijk weergegeven. Hierdoor kunnen de gebruikte analyses worden nagegaan en kunnen andere gebruikers beter begrijpen hoe de uiteindelijke resultaten tot stand zijn gekomen.

## Bijdrage aan reproduceerbaarheid


Een belangrijk doel van het gebruik van GitHub binnen dit onderzoek is het bevorderen van de reproduceerbaarheid. Dit betekent dat een andere gebruiker de beschreven stappen kan volgen en de gebruikte scripts en gegevens kan raadplegen om de analyse opnieuw uit te voeren.

Binnen de repository wordt dit ondersteund door:

Het beschikbaar stellen van de gebruikte R-scripts.
Het documenteren van de verschillende stappen van de analyse.
Het beschikbaar stellen van de gebruikte RNA-sequencingdata.
Het opslaan van de gegenereerde resultaten en figuren.
Het beschrijven van de gebruikte analysemethoden en software.
Het weergeven van de analyseworkflow in een flowchart.

De analyse loopt van de ruwe RNA-sequencingdata via read mapping en feature counting naar de countmatrix. Vervolgens wordt met DESeq2 de differentiële genexpressie bepaald. De verkregen resultaten worden daarna gebruikt voor onder andere de GO- en KEGG-enrichmentanalyses en de pathway-visualisaties.

Door deze stappen afzonderlijk te documenteren en vanuit de repository naar de bijbehorende bestanden te verwijzen, kan de workflow beter worden gevolgd en gecontroleerd.

## Organisatie van de repository


De repository is opgebouwd uit verschillende mappen met ieder een eigen functie. Hierdoor zijn de bestanden die tijdens het onderzoek zijn gebruikt of gegenereerd logisch van elkaar gescheiden.

De belangrijkste onderdelen zijn:

data/ – bevat de gebruikte RNA-sequencingdata en verwerkte gegevens.
scripts/ – bevat het volledige R-script en afzonderlijke scripts voor de verschillende analysemethoden.
figuren/ – bevat de gegenereerde figuren, zoals de volcano plot, GO- en KEGG-visualisaties en pathway-afbeeldingen.
tabellen/ – bevat de tabellen en resultaten die tijdens de analyse zijn verkregen.
bronnen/ – bevat de gebruikte wetenschappelijke bronnen en de AI-disclaimer.
competenties/ – bevat de uitgewerkte competenties, waaronder de documentatie over databeheer en GitHub-beheer.

De mappenstructuur en de functie van de verschillende onderdelen zijn verder beschreven in het Data Stewardship-document.

Daarnaast zijn belangrijke bestanden vanuit de README gekoppeld via hyperlinks. Hierdoor kan een gebruiker rechtstreeks naar scripts, figuren, tabellen en andere relevante onderdelen van de repository navigeren.

## Gebruiksvriendelijkheid

De repository is ingericht zodat de uitgevoerde analyse ook voor een andere gebruiker te volgen is. De README geeft een overzicht van het onderzoek en verwijst naar de verschillende onderdelen van de analyse.

Om de informatie toegankelijk te maken zijn onder andere:

duidelijke namen gebruikt voor bestanden en mappen;
hyperlinks toegevoegd naar relevante scripts, figuren en tabellen;
de verschillende analysemethoden afzonderlijk beschreven;
commentaar toegevoegd aan de R-scripts;
een flowchart gebruikt om de volgorde van de analyse weer te geven.

Hierdoor is het niet noodzakelijk om alle bestanden afzonderlijk te openen om te begrijpen welke stappen tijdens het onderzoek zijn uitgevoerd.

## Versiebeheer met Git en GitHub


Git is gebruikt voor het bijhouden van wijzigingen binnen het project en GitHub fungeert hierbij als online repository. Door wijzigingen met commits op te slaan, blijft de ontwikkeling van de repository inzichtelijk.

Tijdens het project zijn onder andere scripts, documentatie en resultaten aangepast en uitgebreid. Door deze wijzigingen via Git te beheren, kunnen eerdere versies worden teruggevonden wanneer dat nodig is.

Versiebeheer heeft hierbij verschillende voordelen:

eerdere versies van bestanden kunnen worden teruggevonden;
wijzigingen in scripts kunnen worden gecontroleerd;
fouten kunnen gemakkelijker worden hersteld;
de ontwikkeling van het onderzoek blijft inzichtelijk;
verschillende onderdelen van het project kunnen gecontroleerd worden zonder eerdere versies kwijt te raken.

Hoewel het onderzoek individueel is uitgevoerd, biedt GitHub een werkwijze die ook geschikt is voor samenwerking en het gezamenlijk beheren van onderzoeksbestanden.

## Documentatie van het onderzoek


Naast het opslaan van bestanden wordt GitHub gebruikt om de uitgevoerde werkzaamheden te documenteren. De README bevat een beschrijving van het onderzoek, de gebruikte workflow en de belangrijkste resultaten.

Ook de scripts zijn voorzien van commentaar en duidelijke secties. Hierbij wordt beschreven wat een bepaald onderdeel van het script doet en wat het doel van de betreffende analyse-stap is. Voor verschillende onderdelen, zoals mapping, DESeq2, GO en KEGG, zijn daarnaast afzonderlijke scriptbeschrijvingen beschikbaar.

De combinatie van de README, de scripts, de flowchart en de overige documentatie maakt inzichtelijk hoe de ruwe data zijn verwerkt tot de uiteindelijke resultaten.

## Transparantie en toegankelijkheid


Door het onderzoek via GitHub beschikbaar te stellen, zijn de gebruikte scripts, documentatie en resultaten op één centrale locatie verzameld. Hierdoor kan een gebruiker de verschillende onderdelen van het onderzoek bekijken en de relatie tussen de scripts en de resultaten beter begrijpen.

De repository maakt daarmee niet alleen de uiteindelijke resultaten zichtbaar, maar ook de stappen die zijn uitgevoerd om tot deze resultaten te komen. Dit draagt bij aan transparantie binnen het onderzoek.

## Conclusie

GitHub heeft binnen dit onderzoek een belangrijke functie gehad bij het organiseren, documenteren en beheren van de onderzoeksbestanden. Door gebruik te maken van een vaste mappenstructuur, duidelijke verwijzingen, gedocumenteerde scripts en versiebeheer met Git is de analyse overzichtelijk vastgelegd.

De combinatie van de README, scripts, resultaten, flowchart en aanvullende documentatie maakt het mogelijk om de uitgevoerde transcriptomicsanalyse beter te volgen en te controleren. Hierdoor draagt het gebruik van GitHub bij aan de reproduceerbaarheid, transparantie en toegankelijkheid van het onderzoek naar reumatoïde artritis.
