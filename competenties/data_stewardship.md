# Data Stewardship
## Inleiding

Data Stewardship omvat het zorgvuldig verzamelen, beheren, opslaan, documenteren en beschikbaar stellen van onderzoeksgegevens gedurende een onderzoeksproject. Goed databeheer is belangrijk om onderzoeksresultaten betrouwbaar, controleerbaar en reproduceerbaar te maken. Binnen dit onderzoek naar reumatoïde artritis (RA) zijn verschillende soorten bestanden gebruikt, waaronder RNA-sequencingdata, R-scripts, tabellen en figuren. Een duidelijke organisatie van deze bestanden maakt het mogelijk om de uitgevoerde analyses terug te vinden en opnieuw uit te voeren.

## Structuur van de repository

Een duidelijke mappenstructuur zorgt ervoor dat bestanden gemakkelijk terug te vinden zijn en dat de verschillende onderdelen van het onderzoek van elkaar gescheiden blijven. Binnen deze repository zijn de bestanden onderverdeeld in verschillende mappen.

De repository bevat onder andere de volgende mappen:

**data/** – bevat de gebruikte RNA-sequencingdata en de verwerkte data die tijdens de analyse zijn verkregen.

**scripts/** – bevat het volledige R-script waarmee de RNA-sequencingdata zijn verwerkt en geanalyseerd. Daarnaast zijn de verschillende analysemethoden, zoals mapping, DESeq2, GO- en KEGG-analyse, afzonderlijk gedocumenteerd.

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

## Naamgeving van bestanden

Om verwarring tussen bestanden te voorkomen, wordt gebruikgemaakt van herkenbare en beschrijvende bestandsnamen. Namen bevatten waar mogelijk informatie over de inhoud of het doel van het bestand. Voorbeelden hiervan zijn DESeq2_resultaten.csv, GO_BP_results.csv en hsa05323.pathview.png.

Bij het benoemen van bestanden worden waar mogelijk spaties vermeden en worden underscores gebruikt om verschillende woorden van elkaar te scheiden. Door een consistente naamgeving toe te passen, kunnen bestanden sneller worden geïdentificeerd en teruggevonden.

## Versiebeheer

Voor het beheren van de repository wordt gebruikgemaakt van Git en GitHub. Wijzigingen in scripts, documentatie en andere bestanden kunnen hierdoor worden vastgelegd met commits. Hierdoor blijft zichtbaar welke wijzigingen gedurende het project zijn aangebracht.

Versiebeheer maakt het daarnaast mogelijk om eerdere versies van bestanden terug te vinden wanneer een wijziging problemen veroorzaakt. GitHub fungeert hierbij als centrale locatie voor de projectbestanden, documentatie en onderzoeksresultaten.

## Documentatie van scripts

De gebruikte R-scripts zijn voorzien van commentaar en duidelijke secties. Per analyse-stap wordt beschreven wat het doel van de stap is en welke bewerkingen worden uitgevoerd. Waar relevant worden ook gebruikte parameters en voorwaarden toegelicht.

De analyse is daarnaast opgesplitst in afzonderlijke scripts, zodat specifieke onderdelen van de workflow gemakkelijker kunnen worden teruggevonden. Hierbij zijn onder andere het mappen van RNA-sequencingreads, het maken van de countmatrix, de DESeq2-analyse, GO-analyse, KEGG-analyse en Pathview-visualisaties afzonderlijk gedocumenteerd.

Deze vorm van documentatie maakt inzichtelijk hoe de ruwe data uiteindelijk tot de gerapporteerde resultaten hebben geleid.

Opslag en back-ups

Onderzoeksbestanden worden op meerdere locaties bewaard om het risico op gegevensverlies te beperken. De gebruikte scripts en datasets zijn naast de GitHub-repository ook lokaal en via OneDrive opgeslagen.

GitHub wordt voornamelijk gebruikt voor versiebeheer en het beschikbaar maken van de scripts en documentatie. Voor bestanden die niet geschikt zijn om openbaar te publiceren, moet gebruik worden gemaakt van een geschikte beveiligde opslaglocatie.

## Gebruikte tools en bestandsformaten

Voor de verwerking en analyse van de RNA-sequencingdata zijn verschillende bio-informatica-tools en R-packages gebruikt.

Tool/package	Toepassing

**R / RStudio**:	Uitvoeren van de data-analyse en scripts

**Rsubread**:	Mappen van reads en uitvoeren van featureCounts

**Rsamtools**:	Sorteren en indexeren van BAM-bestanden

**DESeq2**:	Differentiële genexpressieanalyse

**clusterProfiler**:	GO- en KEGG-enrichmentanalyses

**org.Hs.eg.db**;	Annotatie en omzetting van humane gen-ID's

**enrichplot**;	Visualisatie van enrichmentresultaten

**EnhancedVolcano**:	Maken van volcano plots

**Pathview**:	Visualiseren van genexpressie op KEGG-pathways

**Git / GitHub**:	Versiebeheer en delen van scripts en documentatie

Tijdens het onderzoek zijn verschillende bestandsformaten gebruikt. FASTQ-bestanden bevatten de oorspronkelijke sequencing reads, BAM-bestanden bevatten de gemapte reads en CSV-bestanden worden gebruikt voor tabellen en analyse-uitvoer. PNG-bestanden worden gebruikt voor figuren en pathway-visualisaties.

## Omgaan met gevoelige gegevens

Bij onderzoeksgegevens afkomstig van patiënten is het belangrijk om rekening te houden met privacy en gegevensbescherming. Persoonsgegevens mogen niet zonder passende bescherming in een openbare repository worden geplaatst.

Voor dit onderzoek is gebruikgemaakt van openbaar beschikbare RNA-sequencingdata. Binnen de repository worden geen direct identificerende persoonsgegevens opgenomen. Hierdoor kunnen de gebruikte scripts en analysebestanden openbaar worden gedeeld zonder dat persoonlijke patiëntinformatie onderdeel wordt van de repository.

Bij toekomstig onderzoek waarbij wel herleidbare patiëntgegevens worden gebruikt, moeten aanvullende maatregelen worden genomen om deze gegevens te beschermen en te voldoen aan de geldende privacywetgeving.

## Open data en hergebruik

Een belangrijk onderdeel van reproduceerbaar onderzoek is het beschikbaar stellen van data en analysemethoden wanneer dit mogelijk en verantwoord is. Voor dit onderzoek is gebruikgemaakt van openbaar beschikbare RNA-sequencingdata. Hierdoor kunnen andere onderzoekers dezelfde dataset gebruiken voor aanvullende analyses of de uitgevoerde resultaten controleren.

Ook de gebruikte scripts en documentatie zijn via GitHub beschikbaar gesteld. Hierdoor is niet alleen het eindresultaat beschikbaar, maar kan ook worden nagegaan welke stappen tijdens de analyse zijn uitgevoerd.

Bij het delen van onderzoeksdata moet altijd worden gecontroleerd of de gegevens openbaar mogen worden gemaakt en of hierbij geen privacygevoelige informatie wordt verspreid.

## FAIR-principes

Bij de inrichting van de repository is rekening gehouden met de vier FAIR-principes: Findable, Accessible, Interoperable en Reusable.

**Findable:** bestanden zijn georganiseerd in een vaste mappenstructuur en hebben beschrijvende namen. Daarnaast kunnen bestanden via de README worden teruggevonden.

**Accessible:** de scripts, documentatie en verschillende onderzoeksresultaten zijn beschikbaar via de GitHub-repository. De gebruikte openbare RNA-sequencingdata zijn eveneens toegankelijk via de aangegeven databron.

**Interoperable:** waar mogelijk worden gangbare bestandsformaten gebruikt, zoals CSV voor tabellen, PNG voor figuren en R-scripts voor de analyse. Daarnaast worden genen gekoppeld aan gestandaardiseerde identificaties zoals Entrez-ID's voor de enrichmentanalyses.

Reusable: de scripts zijn voorzien van documentatie en de gebruikte packages en versies zijn vastgelegd. Hierdoor kunnen andere gebruikers de analysemethode begrijpen en deze eventueel opnieuw uitvoeren of verder ontwikkelen.

## Conclusie

Goed databeheer vormt een belangrijk onderdeel van dit transcriptomicsproject. Door gebruik te maken van een vaste mappenstructuur, duidelijke bestandsnamen, versiebeheer en gedocumenteerde scripts blijven de verschillende onderdelen van het onderzoek overzichtelijk. Daarnaast dragen het gebruik van openbare data, gangbare bestandsformaten en het toepassen van de FAIR-principes bij aan de toegankelijkheid en reproduceerbaarheid van het onderzoek.

De combinatie van GitHub, lokale opslag en OneDrive zorgt ervoor dat belangrijke projectbestanden op meerdere plaatsen beschikbaar zijn. Hierdoor wordt het risico op gegevensverlies beperkt en kunnen de uitgevoerde analyses en resultaten ook na afloop van het project worden teruggevonden en gecontroleerd.
