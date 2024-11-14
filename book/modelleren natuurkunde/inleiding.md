Inleiding in modelleren.

Een van de doelen van de natuurkunde is het beschrijven van natuurkundige fenomenen, bijvoorbeeld beweging van een vallende bal of het temperatuurverloop van afkoelend kopje water.
Een natuurkundig model is een kader waarin je zo'n fenomeen beschrijft,  als  voorbeeld nemen we de valbeweging van een bal met luchtwrijving.
Wat je kan meten is de positie van de bal op verschillende tijdstippen. Dit kan je vervolgens plotten in een grafiek. Hieruit kan je de snelheid de bal op elk moment afleiden met behulp van hellingen.

Waarin je geintresseerd kan zijn is de luchtwrijving dat de bal op elk moment ondervind.
Hier is een formule voor:
Fwl = 0.5*rho*cw*A*v**2. Echter is deze formule ook maar een **model**. Hij past goed voor objecten in een luchtstille ruimte en waar de bal perfect rond is.
Maar hebben we wellicht van turbulentie, of wind in de ruimte, of is de bal een beetje misvormd, of draait om een as, dan gelden weer andere formules. Je moet dus _aannames_ maken om een natuurkundig fenomeen te beschrijven.

Een _aanname_ van het afkoelen van het kopje thee is bijvoorbeeld dat de warmte alleen aan de lucht wordt afgestaan, maar je negeert dan het opwarmen van het keramisch of glazen kopje waar het water in zit. Daarnaast neem je ook aan dat het water stil is in de thee en dus geen draaikolk is.
Een model vor afkoelen van een kopje thee is ook dat de verandering van de temperatuur lineair afhangt van de temperatuur van de thee en de omgevingstemperatuur (wiskundig: dT/dt = c(T-Tomg)) 
Dit zou net zo goed kwadratisch verband kunnen zijn, of wortel, of logaritmisch. Dit is wat je gewoon uitprobeert en kijkt wat het beste past bij de metingen die je doet. Heb je een model dat heel goed past kan je gaan aannemen dat het model ook klopt, tot je een situatie hebt gevonden waarin het model niet meer goed werkt en verfijnt moet worden, of compleet overboord moet worden gegooid.

Een ander voorbeeld daarvan is zwaartekracht. De zogeheten newtoniaanse zwaartekrachtsformule Fz = mg of Fg = G M m / r^2 passen prima bij grote objecten of dicht bij het aardoppervlak. Maar bij grote objecten als zwarte gaten of zware sterren, of hele kleine objecten (quantumwereld) lijken deze formules niet meer passend. Dit zwaartekrachtmodel moet dan dus worden aangepast of overboord worden gegooid; in dit geval het laatste: zwaartekracht is een gevolg van de kromming van ruimte-tijd bij aanwezigheid van een massa. Gaan we nu verder niet op in, het is maar een voorbeeld.

Terug naar het voorbeeld van een vallende bal. We kunnen dus de positie (x), tijd (t) meten en met wat aannames de (v) en Fwl berekenen.

Waar geen formule voor is, is het van te voren bereken van de snelheid op een bepaalde tijdstip van de vallende bal. Immers: als de bal sneller gaat (v groter) wordt de wrijvingskracht (Fwl) groter. Hierdoor wordt de snelheidstoename van de bal minder. Hierdoor wordt de toename van de wrijvingskracht minder, etcetera. Op den duur wordt de luchtwrijvingskracht even groot als de zwaartekracht en neemt de snelheid helemaal niet meer toe.

Om deze beweging dus te kunnen beschrijven hebben we een _numeriek_ model nodig, wat we voor het gemak nu 'modelleren' noemen. Hier heb je een computer voor nodig, die razendsnel de berekeningen kan maken.

Een numeriek model is niets anders dan een algoritme, een recept, waar het fenomeen in wordt beschreven en de grootheden stapsgewijs kunnen worden uitgerekend.

In deze zogeheten JupyterBook ga je met verschillende opdrachten aan de slag om kennis te maken met modelleren. In 5VWO maak je een PO over numeriek modelleren en in 6VWO komt het onderwerp in de vorm van een school- en eindexamen terug. Daar komen we nog op terug.




