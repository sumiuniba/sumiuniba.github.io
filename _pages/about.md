---
permalink: /
title: "Evolučné vysvetlenia kognitívnych skreslení"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**Zadanie práce**
======
Bakalárska práca sa zameriava na evolučné vysvetlenia kognitívnych skreslení - systematických odchýlok od ideálnej racionality v ľudskom myslení. Cieľom je preskúmať, prečo sa tieto skreslenia v priebehu evolúcie vyvinuli, aké adaptačné funkcie mohli plniť v prostredí našich biologických predkov a prečo pretrvávajú aj v súčasnosti, hoci sa v niektorých kontextoch môžu javiť ako nepotrebné alebo dokonca maladaptívne. V práci bude tiež analyzované, spôsobom môžu tieto mechanizmy naďalej poskytovať výhody v modernom svete (napr. pri rýchlom rozhodovaní alebo sociálnej koordinácii), a kriticky zhodnotia kontrast medzi ideálom normatívnej racionality a empiricky pozorovanými vzorcami ľudského myslenia.

**Cieľ práce**
======
Cieľom práce je vysvetliť vznik, pretrvávanie a funkcie vybraných kognitívnych skreslení z evolučnej perspektívy a zhodnotiť ich vzťah k ľudskej racionalite.

**Denník**
======
_23. 2. - 1. 3. 2026_

* Konzultácia so školiteľom.
* Tvorba webovej stránky.

_2. 3. - 8. 3. 2026_

* Výber vhodného frameworku na implementáciu praktickej časti práce.
* Plánovanie implementácie.

_9. 3. - 15. 3. 2026_

* Implementácia jednoduchej simulácie a jej vizualizácie.
* Implementácia agenta bez skreslenia.

_16. 3. - 22. 3. 2026_

* Úprava kódu simulácie.
* Testovanie simulácie.

_23. 3. - 29. 3. 2026_

* Konzultácia so školiteľom.
* Implementácia agenta s averziou voči strate.

_30. 3. - 5. 4. 2026_

* Implementácia agenta s efektom prehnanej sebadôvery.
* Implementácia agenta so stádovým efektom.

_6. 4. - 12. 4. 2026_

* Implementácia mechanizmu na spoluprácu medzi agentmi.
* Zväčšenie mapy a pridanie agentov a objektov do nej.

_13. 4. - 19. 4. 2026_

* Úprava mechanizmu zabezpečujúceho reprodukciu. Pridanie koeficientov pre silu skreslenia. Pridanie mutácie týchto koeficientov pri reprodukcii.
* Testovanie mechanizmu na spoluprácu medzi agentmi.
* Úprava a testovanie objektov mapy.
* Úprava parametrov simulácie a agentov.
* Implementácia mechanizmu na zber dát počas behu simulácie.
* Úprava agenta so stádovým efektom.
* Úprava mapy.

_20. 4. - 26. 4. 2026_

* Dokončenie implementácie simulácie.
* Konzultácia so školiteľom.

_27. 4. - 3. 5. 2026_

* Pridanie averzie voči strate, efektu nadmernej sebadôvery a stádového efektu do teoretickej časti práce.

_4. 5. - 10. 5. 2026_

* Písanie kapitoly Návrh a implementácia simulácie.
* Konzultácia so školiteľom.

_11. 5. - 17. 5. 2026_

* Rozdelenie kapitoly Návrh a implementácia simulácie na dve osobitné kapitoly.
* Dokončenie kapitoly Návrh simulácie.
* Písanie kapitoly Implementácia simulácie.

_18. 5. - 24. 5. 2026_

* Dokončovanie kapitoly Imlemntácia simulácie.

**Vizualizácia simulácie**
======

![Vizualizácia simulácie](/images/simulacia.png)

_Screenshot simulácie zobrazujúci aktuálne rozloženie agentov a veľkosť jednotlivých populácií._

**Ukážka výstupných dát**
======

| Počet krokov | Počet NBA | Počet LA | Počet OC | Počet BW | Vymretie NBA | Vymretie LA | Vymretie OC | Vymretie BW |
|---|---|---|---|---|---|---|---|---|
| 1000 | 0 | 0 | 68 | 0 | 184 | 718 | 1000 | 380 |
| 1000 | 0 | 18 | 60 | 0 | 138 | 1000 | 1000 | 200 |
| 1000 | 0 | 49 | 15 | 0 | 134 | 1000 | 1000 | 200 |

_Nápoveda:_
* NBA (Non Biased Agent) = agent bez skreslenia
* LA (Loss Aversion) = agent s averziou voči strate
* OC (Overconfidence) = agent s efektom prehnanej sebadôvery
* BW (Bandwagon Effect) = agent so stádovým efektom


[Stiahnuť celú ukážku výstupných dát](/files/hunger_games_results.csv)

**Aktuálna verzia práce**
======
[Prezrieť aktuálnu verziu práce](/files/RPBP_bakalárka.pdf)

**Zdroje**
======

1. Sushil Bikhchandani, David Hirshleifer, and Ivo Welch. *A theory of fads, fashion, custom, and cultural change as informational cascades.* Journal of Political Economy, 100(5):992–1026, 1992.

2. Hershey H Friedman. *Cognitive biases and their influence on critical thinking and scientific reasoning: A practical guide for students and teachers.* Available at SSRN 2958800, 2023.

3. David Gal and Derek D Rucker. *The loss of loss aversion: Will it loom larger than its gain?* Journal of Consumer Psychology, 28(3):497–516, 2018.

4. Andrew Galperin and Martie G Haselton. *Error management and the evolution of cognitive bias.* In *Social Thinking and Interpersonal Behavior*, pages 45–63. Psychology Press, 2012.

5. Gerd Gigerenzer and Wolfgang Gaissmaier. *Heuristic decision making.* Annual Review of Psychology, 62:451–482, 2011.

6. W. D. Hamilton. *Geometry for the selfish herd.* Journal of Theoretical Biology, 31(2):295–311, 1971.

7. Martie G Haselton and Daniel Nettle. *The paranoid optimist: An integrative evolutionary model of cognitive biases.* Personality and Social Psychology Review, 10(1):47–66, 2006.

8. Martie G Haselton, Daniel Nettle, and Paul W Andrews. *The evolution of cognitive bias.* The Handbook of Evolutionary Psychology, pages 724–746, 2015.

9. Joe Henrich and Robert Boyd. *The evolution of conformist transmission and the emergence of between-group differences.* Evolution and Human Behavior, 19(4):215–241, 1998.

10. Dominic D. P. Johnson, Daniel T. Blumstein, James H. Fowler, and Martie G. Haselton. *The evolution of error: Error management, cognitive constraints, and adaptive decision-making biases.* Trends in Ecology & Evolution, 28(8):474–481, 2013.

11. Dominic D. P. Johnson and James H. Fowler. *The evolution of overconfidence.* Nature, 477(7364):317–320, 2011.

12. Daniel Kahneman. *Thinking, Fast and Slow.* Penguin Books, 2012.

13. Daniel Kahneman, Jack L. Knetsch, and Richard H. Thaler. *Anomalies: The endowment effect, loss aversion, and status quo bias.* Journal of Economic Perspectives, 5(1):193–206, 1991.

14. Regis K Kakinohana and Ronaldo Pilati. *Differences in decisions affected by cognitive biases: examining human values, need for cognition, and numeracy.* Psicologia: Reflexão e Crítica, 36(1):26, 2023.

15. Norman Knyazev and Harrie Oosterhuis. *The bandwagon effect: Not just another bias.* In *Proceedings of the 2022 ACM SIGIR International Conference on Theory of Information Retrieval*, pages 243–253, 2022.

16. J. E. Korteling, J. Sassen-van Meer, A. Toet, and H. J. H. C. van Veen. *Neuro-evolutionary framework for cognitive biases.* Rapport TNO, R10611, 2020.

17. Don A. Moore and Paul J. Healy. *The trouble with overconfidence.* Psychological Review, 115(2):502, 2008.

18. Uwe Peters. *What is the function of confirmation bias?* Erkenntnis, 87(3):1351–1376, 2022.

19. Project Mesa Contributors. *Mesa: Agent-based modeling in Python 3+.* GitHub repository, 2025. https://github.com/mesa/mesa

20. David C. Queller. *A general model for kin selection.* Evolution, 46(2):376–380, 1992.

21. Shelley E. Taylor and Jonathon D. Brown. *Illusion and well-being: A social psychological perspective on mental health.* Psychological Bulletin, 103(2):193, 1988.

22. Ewout ter Hoeven, Jan Kwakkel, Vincent Hess, Thomas Pike, Boyu Wang, rht, and Jackie Kazil. *Mesa 3: Agent-based modeling with Python in 2025.* Journal of Open Source Software, 10(107):7668, 2025. Použitá verzia softvéru: 3.3.1.

23. Peter M Todd, Ralph Hertwig, and Ulrich Hoffrage. *Evolutionary cognitive psychology.* The Handbook of Evolutionary Psychology, pages 776–802, 2015.

24. Amos Tversky and Daniel Kahneman. *Judgment under uncertainty: Heuristics and biases.* Science, 185(4157):1124–1131, 1974.

25. Hans Van Eyghen. *Cognitive bias: Phylogenesis or ontogenesis?* Frontiers in Psychology, 13:892829, 2022.
