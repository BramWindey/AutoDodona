# AutoDodona


Waar vindt u de code op GitHub?
Zoek naar "Releases" op de rechterkant van de pagina's, ga naar tags en kies hier de versie die u wenst. Ik raad altijd de nieuwste versie aan.


**Gebruiksaanwijzingen**

Voorlopig moet dit programma worden uitgevoerd in een IDE, bijvoorbeel PyCharm. Zorg dat de volgende bestanden zich in dezelfde map bevinden:
-main.py
-webscraper.py
-code_assemble.py
-API-token.txt
-program.txt

Zorg bij een eerste gebruik dat u een API-token genereert in Dodona, en dit in dit tekst bestand kleeft. Lees hier hoe waar u dit token kan genereren: https://docs.dodona.be/nl/guides/creating-an-api-token/
Na deze eerste keer zal dit niet meer nodig zijn. (Behalve bij het updaten naar een nieuwe versie, daarbij moet u uw token van het oude tekstbestand kopiëren naar het nieuwe bestand, of het oude bestand kopiëren, of de oude .py-bestanden vervangen door de nieuwe.)

Bij een eerste keer zal u ook de volgende modules moeten installeren:
-requests
-bs4
-itertools
-pyperclip
In PyCharm kan dit door in webscraper.py en code_assembly over de overeenkomstige namen van de modules te "zweven" en op de link "install module" te klikken. 

Na dit beginnersongemak bent u klaar om het programma te gebruiken. Voer main.py uit, en volg de instructies van het programma. 


**Programma-instructies**

Bij het plakken van de link moet u opletten, u moet de correcte link kleven. 
Deze link krijgt u als volgt:
-navigeer naar de oefening op Dodona
-dien deze leeg in
-als niet alle testcases fout zijn, dien dan 'print("foo")' in als programma, sla anders deze stap over (overbodige stap bij functies, zie V2.0)
-boven het rode kruis met "Fout" klikt u nu op '#1', dit nummer kan verschillen
-u zit nu op de juiste pagina, kopieer de link bovenaan uw browser, en plak deze in het programma, en druk op enter

Hierna wordt u het aantal outputs gevraagd. Kijk hiervoor terug naar de Dodona-resultatenpagina die u hierboven verkreeg, en tel hoeveel verschillende outputs (per input) er onder de categorie "Verwachte uitvoer" staan. Gewoonlijk is dit een laag getal tussen de 1 en 5. Geef in in het programma en druk op enter.

Hierna bent u klaar. Wanneer het programma meldt dat de code op het klipbord staat, betekent dit dat het klaar is met werken (normaalgezien duurt dit maximum een paar seconden), en kan u terug naar de oefening op Dodona gaan. Op de plaats waar de programmacode terechtkomt kan u onmiddelijk de gegenereerde code kleven. Mocht dit niet het geval zijn, dan staat de gegenereerde code in "program.txt". Open dit bestand en kopieer de inhoud.


**Beperkingen**

Vanaf pre-release V2.0 en verder worden ook functies ondersteund. Let wel op: functies met naamargumenten zijn NIET ondersteund, en staan ook niet op de planning om ondersteund te worden. Dit wegens vermoedelijk onmogelijk te zijn.

Het kan gebeuren dat bij het indienen van de code Dodona de melding geeft dat de code te groot is. Hier kan jammergenoeg niets aan gedaan worden, het is dan aan u om de oefening al redenerend uit te werken. 

Het aantal verwachtte outputs moet worden opgegeven. Dit is niet wenselijk, maar ik zag nog geen simpele oplossing voor dit probleem. Hopelijk kan dit worden opgelost in verdere updates.

Het programma moet uitgevoerd worden binnen een IDE, wat het natuurlijk minder toegankelijk maakt. Dit wordt hopelijk in in een toekomstige update simpeler gemaakt.
