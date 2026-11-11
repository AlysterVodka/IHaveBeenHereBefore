- [ ] lift gaat niet open in de spa
- [ ] laatste level af
- [ ] bugfixes
### release in december
- [x] crosshair verdwijnt af en toe
- [ ] directions / geef de speler meer purpose
- [x] lift level kiezen
- [ ] save game system : elk level wordt gesaved --> voeg alvast een IsDemo toe, zodat ie dan niet saved
	- [ ] save level
	- [ ] save position
	- [ ] save progress [is die er dan?] --> elevator, dus welke levels er al zijn gedaan
	- [ ] bij startup [continue] --> kies deze settings [load game]
	--> het precieze gedrag moet zijn: speler speelt een level uit - dit level wordt als huidig level opgeslagen. daarna bij het saven in het nieuwe level naar vorig level opgeslagen. dit is het level wat dan in de map gemarkeerd wordt als uitgespeeld. 
	- je moet altijd in de lift terugkomen
#### dus to do daarvoor:
- level registrator: bij elk level dat wordt geladen, wordt ergens geregistreerd welk level dat is [bool = true 76]

- [ ] add kiddiepools and weird waterstatues [clown]
- [ ] tight spaces
- [ ] earthquakes and other strange anomalies that are tension heightening
- [ ] dark spaces
- [x] moving water https://www.youtube.com/watch?v=FqkS6Ke0ouE
	- [ ] https://www.youtube.com/watch?v=yL6OpVVevgg  #ingeborg
	- [ ] https://www.youtube.com/watch?v=RjU9Q_B2GR0
- [ ] kantoor
- [ ] hotel
- [ ] briefjes / graffiti cues

- [x] wading sound implementation
- [ ] floaty https://www.versluis.com/2023/05/making-things-float-on-water-in-unreal-engine-5-1-and-5-2/
- [x] crouch smoothing
- [ ] soft body https://heyyocg.link/en/niagara-easy-soft-body-simulation/
- [x] lvl1 graffiti op muren
- [ ] crouch geluid

#### Geluiden / Events
stage 1
- [ ] voetstappen die steeds stoppen
- [x] graffiti
- [ ] graffiti fiksen [overlapt]
- [ ] 1 rondje minder
- [x] liften resetten na elk rondje

stage 2
- [ ] duikplankgeluid wordt afgekapt -- nakijken
- [ ] standbeeld onder water

stage 3 : binnenspeeltuin
- [ ] echoes
- [ ] deuren open einde
- [ ] alles dichtbouwen
- [ ] zorgen dat je nergens klem kan komen te zitten [crouchspace]
- [ ] fov aanpassen
- [ ] miss iets minder donker
- [ ] lichtslangen werken niet meer

stage 4: doolhof met bricks, licht en met veel gangen
- [ ] maze game?
- [ ] meer niveaus?

stage 5: hotelkamers
eindeloze gang [loop] met andere kamertjes, kamertjes maken nieuwe gangen.
elk kamertje heeft een mini aanpassing

