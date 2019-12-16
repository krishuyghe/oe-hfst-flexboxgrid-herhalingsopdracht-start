# oe-hfst-flexboxgrid-herhalingsopdracht-start
We maken een eigen versie van de zombies-website uit de cursus.
Maak een responsive website m.b.v. grid, flexbox en mediaqueries.
Gaandeweg voorzien we soms nog wat extra functionaliteiten die je zelf kan onderzoeken.
**Lees elke individuele opdracht eerst volledig door!**

Nuttige links:
- https://css-tricks.com/snippets/css/complete-guide-grid/
- https://fonts.google.com/
- https://fontawesome.com/ 

## Opdracht 1
- maak een eenvoudige pagina die als basis een grid-layout heeft.
  - de pagina bevat een header, 2 asides, een main en een footer
  - Voorzie in elk element een p-tag, zodat je straks kan zien waar alles terecht komt op het scherm
  - Probeer Emmet eens uit: tik het volgende in `p>lorem2000` en druk op `TAB`.

- Deze elementen worden op een grid geplaatst:
  - Helemaal bovenaan de pagina is er een schermvullende balk voor de header, helemaal onderaan een schemvullende balk voor de footer.
  - In het midden van de grid staat de main, die links en rechts ervan plaats maakt voor aside informatie (bv. advertenties).
  - Gebruik grid-template-areas om de elementen te positioneren binnen het grid.
  - Geef elke area z'n eigen kleur (om je te helpen bij het visualiseren).
  
## Opdracht 2
- Maak je website responsive. Wanneer het scherm kleiner wordt dan 960px nemen alle elementen de volledige breedte in en worden ze onder elkaar weergegeven. Er is echter 1 uitzondering: de asides worden wel naast elkaar weergegeven! Er is dus eerst plaats voor een header, dan voor de main, dan komende de twee asides naast elkaar te staan, dan de footer.
- Op mobile vinden we de aside information toch maar niets. Zorg ervoor dat je op mobile, wanneer de schermbreedte kleiner is dan 512px, de asides niet meer ziet.

  
## Opdracht 3
- Wanneer de pagina afgedrukt wordt, willen we dat de gebruiker enkel de tekst uit de main hoeft af te drukken om het milieu te sparen. Alle andere info (uit de asides, header, etc) willen we niet zien wanneer er geprint wordt. Voorzie dit.

Je pagina zou er nu ongeveer zo moeten uitzien:
![PC](../master/screenshots/1.bmp)
![Tablet](../master/screenshots/2.bmp)
![Mobile](../master/screenshots/3.bmp)

Bij printweergave zie je dit:
![Afdrukweergave](../master/screenshots/4.bmp)

## Opdracht 4
- Verwijder de p-tag die je eerder in de main zette.
- Voer de emmetinstructie `article*10>h2>lorem3^p*2>lorem` + `TAB` uit. Dit zorgt ervoor dat we 10 artikels maken die elk een hoofding hebben van 3 woorden en twee p-tags met wat tekst in.
- Zorg er nu voor dat de main van je pagina flex ondersteunt. Je plaats dus met andere woorden een flexbox binnen je grid.
- De artikels zijn 50% breed, zodat er twee kolommen gecreëerd worden.

## Opdracht 5
- We voorzien een vlaggetje aan elk artikel, zodat we ze kunnen nummeren.
- Voeg aan elk artikel een div toe. Deze div is telkens het eerste child van het arikel.
-	Geef deze divs de klassenaam `flag`
-	Zorg ervoor dat het vlaggetje in de rechterhoek van elk artikel gepositioneerd wordt. Maak hiervoor gebruik van een absolute positionering, binnen het artikel.
![Opdracht 5](../master/screenshots/5.bmp)

## Opdracht 6
We willen ook een help-knop voorzien in de rechter onderhoek. Deze knop neemt de vorm aan van een div-element! Deze knop is permanent zichtbaar halverwege de pagina (tegen de scrollbalk). Ook wanneer je scrollt is de knop steeds zichbaar op dezelfde plaats. Maak gebruik van passende positionering om deze knop te voorzien.
Zorg er ook voor dat wanneer een gebruiker over het element beweegt er iets aan de opmaak van het element verandert. Zo weet de gebruiker dat hij iets kan doen.
![Opdracht 6](../master/screenshots/6.bmp)

FOTO
## Opdracht 7
We willen er nu voor zorgen dat het eerste artikel in de spotlight staat. Schrijf een passende css-selector om de tekst van het eerste artikel een ander kleur te geven.

## Opdracht 8
Verander het lettertype voor de volledige pagina. Maak hiervoor eventueel gebruik van een Google Font. Dat doe je helemaal bovenaan in je css met de @import at-rule. Zoek uit hoe dit werkt; op de website van Google vind je de nodige informatie.
 
## Opdracht 9
Maak de navigatie voor je pagina. Plaats een logo dat de volledige schermgrootte (width 100%) inneemt.
Indien je de opdracht exact heb opgevolgd, krijg je nu problemen met het plaatsen van de afbeelding binnen het grid. Los dit op.
Centreer de afbeelding en de p-tag. Verander de inhoud van de p-tag naar “Zombie News Inc.”.
**Denk eraan dat je ontwikkelde voor verschillende schermen!**
Maak vervolgens een nav-element met daarin een lijst om te kunnen navigeren naar ‘Home’ en ‘Contact’. Je hoeft deze pagina’s niet te voorzien. Op een pc-scherm worden de navigatie-items naast elkaar weergegeven, op mobiele apparaten onder elkaar.
![Opdracht 9a](../master/screenshots/7.bmp)
![Opdracht 9b](../master/screenshots/8.bmp)
  
## Opdracht 10
Voorzie in de linker aside een afbeelding met reclame voor een halloween-evenement.
Voorzie in de rechter aside een invulveld waar de gebruiker zich kan inschrijven op een nieuwsbrief. De data uit het formulier wordt effectief verstuurd.
Gebruik hiervoor http://jkorpela.fi/cgi-bin/echo.cgi

## Eindresultaat
![eindresultaat](../master/screenshots/9.bmp)
