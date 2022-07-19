Paper: Swarm SLAM: Challenges and Perspectives

URL: https://www.frontiersin.org/articles/10.3389/frobt.2021.618268/full

Year: 2021

Tags: swarm robotics, SLAM, distributed systems, mapping, exploration schemes, localization

Notes: * Review o swarm SLAMu s nastinenim toho, co by takovy SLAM mel umet. V 2021 prakticky neprozkoumane, jsou tam asi dva zdroje. Zni to jako zajimavy odrazovy mustek. 
       * Zajimave problemy: *distribuovana lokalizace, spojovani map a vzajemna lokalizace* + *vymena dat* (reseno v MAPC?)
       * IDEA: swarm mapping/SLAM muze byt nepresny, pravidla ale musi byt rychle/levne. 
       * Priklad: mam mapu kopce a snazim se urychlene zmapovat lavinu. Nezajima me kazda zavej, ale co se kam pohnulo, kolik toho bylo a jak velky pruser to je. 
       * Odkazy na clanky o SLAMech + explorations.

================ 

Paper: Random Walks in Swarm Robotics: An Experiment with Kilobots

Year: 2016

URL: https://link.springer.com/content/pdf/10.1007/978-3-319-44427-7.pdf

Tags: swarm robotics, random walk, LW, CTW, Levy walk, correlated random walk

Notes:  * *Přenos informace ve swarmu* - jak a co? - šlo by rozpracovat, 
        * correlated random walks, Levy random walks a jejich praktické aplikace v přírodě.
        * V realne situaci je treba zvysit perzistenci korelovane random walk kvůli tomu, ze realny robot prirozene "ztraci smer" (narazy, deadreckoning, driftovani navigace nebo proste nepresnosti elektromechanikymechaniky). 

================

Paper: Partial Swarm SLAM for Intelligent Navigation (preprint)

Year: 2022

URL: https://www.researchgate.net/publication/360757653_Partial_Swarm_SLAM_for_Intelligent_Navigation

Tags: swarm robotics, searching, SLAM

Notes: (nečteno detailně, jen hlavní myšelnky) Spíš než SLAM je to hledání cíle. Vlastně se jedná o binární vyhledávání kombinované s  mravenčním algoritmem: hejno letí a na velké překážce se rozdělí na půlky, jedna letí doprava, druhá doleva. Na místech dělení dochází k zaznamenání souřadnic ("feromony"). Poté, co někdo najde cíl, vyšle broadcastem své souřadnice(?) a ostatní k němu podle feromonů doletí. Jen simulace. Jak to bude fungovat v reálu? Co broadcast? 

================

Paper: Distributed evolution for swarm robotics

Year: 2007

URL: https://www.proquest.com/openview/d1b040e949f6769fcbca740a2c4a19d9/1?pq-origsite=gscholar&cbl=18750

Tags:  swarm

Notes: Nečetl jsem, jelikož je to docela staré, ale možná se to někdy bude hodit. Je to dizertačka o swarm robotice.

================

Paper: Reflections on the future of swarm robotics

Year: 2021

URL: https://hal.archives-ouvertes.fr/hal-03362864/document

Tags: swarm robotics, future, overview, challenges,  

Notes: 
* Otevřené problémy swarm robotiky: principy vysokoúrovňového řízení, kombinace low-level chování na úrovni jednotlivce a high-level chování na úrovni celku, kombinace 
centralizovaného a decentralizovaného přístupu.
* Údajně se během následujících let ukážou algoritmy pro autonomní učení hejn tak, aby se hejno samo rozhodlo, jak nejlépe dosáhnout řešení dané úlohy
* Problém: nízký výkon jedince (nebo moc požadavků na něj)
* Opět problém řízení na low a high levelu, *v současné době asi nejzajímavější*, spolu s dosažením fault tolerance, úplnosti, škálovatelnosti... + decentralizace vs centralizace - jako zajímavé se jeví centralizované chování s tím, že pokud centrum není dostupné, přepíná se (automaticky v nejlepším případě) na self-organized
* S ML a AI příchází i explainability/reasonability - schopnost vysvětlit své chování
* Chybí společný framework na úrovni ROSu
* přeskočeny nanoboty, security, adaptability, human-swarm interaction
* problém heterogenity vs homogenity neboli "nevyplatí se mít tam víc druhů?"

================

Paper: 

Year: 

URL: 

Tags: 

Notes: 

================

Paper: 

Year: 

URL: 

Tags: 

Notes: 

================

Paper: 

Year: 

URL: 

Tags: 

Notes: 