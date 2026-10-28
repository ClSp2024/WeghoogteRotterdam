# WeghoogteRotterdam
Weghoogteverschilkaart 2025 Rotterdam
Een dataset die 2-jaarlijks (indien gewenst jaarlijks) wordt geupdate, waarin het uitgiftepeil van de wegen wordt vergeleken met de actuele weghoogte. In deze dataset is hiervoor het maaiveld uit het hoogtebestand 2025 van de gemeente Rotterdam als uitgangspunt genomen. Voor ieder individueel wegvak is berekend het oppervlak (m2) van het wegvak, het volume (m3) dat nodig is om het wegvak -indien onder uitgiftepeil- naar uitgiftepeil te brengen, het gemiddelde verschil (m) dat het wegvak heeft tov uitgiftepeil en de standaardafwijking en minimale en maximale waarde daarvan. Extra toevoeging is de gemiddelde weghoogte van dat vak en de standaardafwijking daarvan. Als deze laatste groot is dan zijn er veel hoogteverschillen binnen het vak. 
De bovenstaande beschrijving betreft achtereenvolgens de velden : Opp, Volume, Gemiddelde_Verschil, Stdev_Verschil, Minimum_Verschil, Maximum_Verschil, Gemiddelde_Weghoogte, Stdev_Weghoogte.
De uitgiftepeilen zijn berekend door een IDW inverse distance interpolatie van de peilpunten met status = V. Er is gekozen om geen maximale interpolatieafstand in te stellen en 12 punten te kiezen om de interpolatiewaarde te bepalen, power=2. 

Dekkingsgebied: wegen van heel gemeente Rotterdam

Opmerking: de hoogste klasse (maaiveld meer dan 50 cm boven UGP, ofwel de berekende waarde kleiner dan -0,5 m) heeft een afwijkende kleur gekregen omdat dit meestal betekent dat de uitgiftepeilen niet horen bij dat wegvak maar bij een lager en nabij gelegen vak. Dit doet zich voor oa bij bruggen en dijken.
