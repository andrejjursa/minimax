Katalóg požiadaviek
===================


## Predmet špecifikácie
Táto špecifikácia požiadaviek popisuje používateľské a funkčné požiadavky na prvú verziu aplikácie na vizualizáciu rozhodovacieho procesu algoritmu minimax.

Táto aplikácia bude slúžiť na vizualizáciu algoritmu minimax v hre piškvorky. Bude používaná na prednáškach predmetu `Úvod do umelej inteligencie` na grafické znázornenie rozhodovacieho procesu tohto jednoduchého no dobre predstaviteľného algoritmu.


## Špecifikácia požiadaviek
Aplikácia musi byť graficky jednoduchá a interaktívna vzhľadom na jej určenie. Musí byť spustiteľná aj v proprietárnom prostredí MS Windows, ktoré je používané na prednáškach ako premietač.

### Grafické rozhranie
Keďže grafické rozhranie bude premietané projektorom, musí byť dostatočne kontrastné a prispôsobiteľné svetelným a iným podmienkam. Týmto sa rozumie najmä nezávislosť od rozlíšenia výstupného zariadenia a podpora farebných schém.

Z hľadiska rozloženia grafických prvkov bude obrazovka rozdelená na dve časti, ľavú a pravú. Jedna bude zobrazovať momentálny stav hry (rozloženie herných kameňov a informácia o tom, kto je na ťahu), a druhá bude vizualizovať stav rozhodovacieho stromu vygenerovaného algoritmom minimax.

### Užívateľské rozhranie
Ovládanie aplikácie nebude vyžadovať použitie myši, aj keď môže obsahovať "klikateľné" prvky.

Aplikácia môže byť používaná v dvoch režimoch:

#### Vizualizačný režim
Režim, v ktorom je aplikácia spustená a ďalej sa jej netreba venovať - bude v rozumných intervaloch sama hrať hru, až kým hra neskončí.

#### Interaktívny režim
Alebo aj "prednáškový" režím, v ktorom je aplikácia ručne krokovateľná.  Takto môže byť na prednáške použitá ako konkrétny príklad, keďže bez užívateľského vstupu sa na jej grafickom výstupe nič nezmení.


## Ďalšie požiadavky
### Výkonnostné požiadavky
Keďže aplikácia je určená na použitie na prednáškach, je neprijateľné, aby v interaktívnom režime prechody medzi stavmi trvali viac ako zopár desiatok milisekúnd. Tomuto bol samozrejme prispôsobený výber programovacieho prostredia, a bude na to kladený dôraz počas celého procesu vývoja aplikácie, rovnako ako pri jej testovaní.

### Dostupnosť
Aplikácia bude spustiteľná na väčšine moderných operačných systémoch, no testovaná a ladená bude iba v prostrediach MS Windows a GNU/Linux.

Bude sprístupnená ako slobodný (free) softvér chránený tzv. "copyleft" licenciou, čím je zároveň zaručené, že na jej vývoj nebude použitý žiadny softvér, ktorý používa iný druh licencovania.

Zvolená licencia je [GNU General Public Licence, verzia 3](http://www.gnu.org/licenses/gpl-3.0.en.html).
