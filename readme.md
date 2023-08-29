U levert het bestand waar u eerder mee geoefend hebt (van de calculator) functionerend op. De calculator moet geheel werken zoals u van een calculator gewend bent. Hiervoor moet u best een aantal denkstappen doorlopen en wellicht hier en daar Google gebruiken om antwoorden te vinden. Dat is de praktijk van de webontwikkelaar dus ook hier zult u handig in moeten worden.
Hoe evalueert u of er al een waarde in myInput staat? Er staat weliswaar een 0 in het display maar dit is een placeholder, géén waarde. De waarde in de initiële staat is "". Als dit true is, mag een nieuw getal ingevoerd worden.
Hoe gaat u er bijvoorbeeld voor zorgen dat als u op een operator klikt, het ingevoerde cijfer correct opgeslagen wordt en u vervolgens een nieuw cijfer kunt invoeren?
Hoe zorgt u ervoor dat als er een nul in het display staat deze moet worden vervangen door het eerste cijfer dat ingetoetst wordt, maar elk volgend cijfer eraan toegevoegd moet worden?
Hoe zorgt u ervoor dat de gebruiker slecht éénmaal een punt kan intoetsen?
Hoe zorgt u ervoor dat er niet een aantal nullen achter elkaar ingetoetst kunnen worden tenzij deze vooraf gegaan zijn door een ander cijfer of een punt?
Hoe zorgt u ervoor dat de juiste operators uitgevoerd worden?
U hebt een aantal if / else if / else statements nodig én u moet de invoerwaarden van de berekeningen in variabelen (let) opslaan. Ook moet u de gekozen operator in een let opslaan.
U kunt ook gebruikmaken van een lege 'if' statement, bijvoorbeeld dat er niets moet gebeuren als er opnieuw een punt wordt getoetst als er al een punt staat.
Om te controleren of er een "." of een 0 in het scherm staat, kunt u gebruikmaken van een method van het string object: indexOf(). Zie deze website. U maakt hier pas in het volgende hoofdstuk kennis mee maar zonder deze method kunt u niet controleren of er in het reeds ingevoerde getal een "." aanwezig is. Als dit namelijk het geval is, retourneert de method een getal dat aangeeft op welke positie (index) de punt staat. Als er géén punt aanwezig is, retourneert de method de waarde -1. Dat is in dit geval belangrijk informatie en kunt u gebruiken in een if statement:

In de calculator kunt u direct de waarde van het HTML input element evalueren – controleren of er al een punt in het getal staat én of er opnieuw een punt is getoetst:

De voorwaarden op een rij:
De gebruikte getallen slaat u op in let en const, geen var.
U past alle bewerkingen toe (de operators +, -, * en /).
U gebruikt conditionals om de juiste sommen te kunnen maken.
U gebruikt de invoer zowel om op te tellen als samen te voegen tot string (concatenation).
U schrijft eigen functies waar nodig.
U zet waarden van variabelen om van data type (casting) waar nodig.
U laat zien hoe u met globale en lokale variabelen werkt.
U gebruikt Event handlers voor user events.
Uw script werkt foutloos.
U hebt oplossingen gevonden voor alle uitdagingen.

Voor elk correct uitgevoerd aspect ontvangt u 1 punt. Het kan zijn dat u niet voor alle uitdagingen een oplossing hebt gevonden, het is ook best lastig om alle denkstappen correct te vertalen naar code. Dit is niet erg, als tenminste alle berekeningen kloppen en werken.
Let er wel op dat het vooral om de oefening en de feedback van uw docent gaat, het cijfer is immers formatief, alleen het cijfer dat u voor het CIW-examen behaalt, is bepalend voor het eindcijfer van deze module.
