Data Stewardship
# Inleiding

Data Stewardship omvat het zorgvuldig beheren, organiseren, opslaan en documenteren van onderzoeksgegevens gedurende de volledige onderzoeksperiode. Het doel hiervan is om gegevens betrouwbaar, reproduceerbaar en herbruikbaar te maken.

## Structuur van de repository

Een duidelijke mappenstructuur zorgt ervoor dat bestanden gemakkelijk terug te vinden zijn en dat de verschillende onderdelen van het onderzoek van elkaar gescheiden blijven. Binnen deze repository zijn de bestanden onderverdeeld in verschillende mappen.

De repository bevat onder andere de volgende mappen:

**data/** – bevat de gebruikte RNA-sequencingdata en de verwerkte data die tijdens de analyse zijn verkregen.

**scripts/ ** – bevat het volledige R-script waarmee de RNA-sequencingdata zijn verwerkt en geanalyseerd. Daarnaast zijn de verschillende analysemethoden, zoals mapping, DESeq2, GO- en KEGG-analyse, afzonderlijk gedocumenteerd.

**figuren/** – bevat de figuren die tijdens de analyse zijn gemaakt, waaronder de volcano plot, GO- en KEGG-resultaten en de gegenereerde pathway-visualisaties.

**tabellen/** – bevat de tabellen met resultaten uit de analyses.

**bronnen/** – bevat de gebruikte wetenschappelijke bronnen en de AI-disclaimer.

**competenties/** – bevat de uitgewerkte competenties en de bijbehorende documentatie over databeheer.

Door de bestanden op deze manier te organiseren, zijn ruwe data, scripts, resultaten en documentatie van elkaar gescheiden. Hierdoor kunnen de verschillende stappen van het onderzoek gemakkelijker worden teruggevonden en gecontroleerd. De resultaten en figuren zijn vanuit de README via hyperlinks toegankelijk gemaakt, zodat de gebruiker direct naar de betreffende bestanden kan navigeren.

De gebruikte scripts zijn voorzien van commentaar waarin het doel van de verschillende analyse-stappen en belangrijke parameters worden beschreven. Hierdoor is inzichtelijk welke bewerkingen zijn uitgevoerd en waarvoor deze zijn gebruikt.

## Toepassing binnen dit onderzoek

Binnen dit transcriptomicsonderzoek naar reumatoïde artritis zijn verschillende maatregelen genomen om een goede dataorganisatie te waarborgen. De ruwe RNA-sequencing data, scripts, resultaten en figuren zijn overzichtelijk gestructureerd in afzonderlijke mappen.

Alle bio-informatica analyses zijn uitgevoerd met behulp van R-scripts die voorzien zijn van duidelijke kopjes en commentaar, zodat iedere stap van de analyse gevolgd en opnieuw uitgevoerd kan worden. Hierbij zijn onder andere de stappen voor read alignment, het maken van een countmatrix, differentiële genexpressieanalyse, KEGG-analyse, Gene Ontology-analyse en Pathview-visualisaties gedocumenteerd.

De resultaten zijn opgeslagen in herbruikbare bestandsformaten zoals CSV en PNG, waardoor deze eenvoudig kunnen worden gedeeld en opnieuw geanalyseerd.

## FAIR-principes

Bij het beheren van de gegevens is rekening gehouden met de FAIR-principes:

Findable: bestanden zijn voorzien van duidelijke namen en een overzichtelijke mappenstructuur.
Accessible: de data en scripts zijn beschikbaar via GitHub.
Interoperable: gebruik van gangbare bestandsformaten zoals CSV, PNG en R-scripts.
Reusable: uitgebreide documentatie maakt het mogelijk om de analyse opnieuw uit te voeren en verder uit te bouwen.
