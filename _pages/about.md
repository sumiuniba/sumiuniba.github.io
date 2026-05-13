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

_27. 4. - 3. 5. 2026_

* Pridanie averzie voči strate, efektu nadmernej sebadôvery a stádového efektu do teoretickej časti práce.

_4. 5. - 10. 5. 2026_

* Písanie kapitoly Návrh a implementácia simulácie.

_11. 5. - 17. 5. 2026_

**Vizualizácia simulácie**
======

![Vizualizácia simulácie](/images/simulacia.png)

_Screenshot simulácie zobrazujúci aktuálne rozloženie agentov v prostredí a veľkosť ich populácie._

**Ukážka výstupných dát**
======

| Počet krokov | Počet NBA | Počet LA | Počet OC | Počet BW | Vymretie NBA | Vymretie LA | Vymretie OC | Vymretie BW |
|---|---|---|---|---|---|---|---|---|
| 1000 | 0 | 0 | 68 | 0 | 184 | 718 | 1000 | 380 |
| 1000 | 0 | 18 | 60 | 0 | 138 | 1000 | 1000 | 200 |
| 1000 | 0 | 49 | 15 | 0 | 134 | 1000 | 1000 | 200 |

_Nápoveda:_
* NBA (Non Biased Agent) = agent bez skreslenia
* LA (Loss Aversion) = agent s averiou voči strate
* OC (Overconfidence) = agent s efektom prehnanej sebadôvery
* BW (Bandwagon Effect) = agent so stádovým efektom


[Stiahnuť celú ukážku dát](/data/hunger_games_results.csv)

**Zrdoje**
======

**Zdroje**
======

* Bellman, Richard. “A Markovian Decision Process.” *Journal of Mathematics and Mechanics*, 6(5):679–684, 1957.

* Bikhchandani, Sushil, David Hirshleifer, and Ivo Welch. “A Theory of Fads, Fashion, Custom, and Cultural Change as Informational Cascades.” *Journal of Political Economy*, 100(5):992–1026, 1992.

* Bindra, Sunali, Deepika Sharma, Nakul Parameswar, Sanjay Dhir, and Justin Paul. “Bandwagon Effect Revisited: A Systematic Review to Develop Future Research Agenda.” *Journal of Business Research*, 143:305–317, 2022.

* Friedman, Hershey H. “Cognitive Biases and Their Influence on Critical Thinking and Scientific Reasoning: A Practical Guide for Students and Teachers.” *Available at SSRN 2958800*, 2023.

* Gal, David, and Derek D. Rucker. “The Loss of Loss Aversion: Will It Loom Larger Than Its Gain?” *Journal of Consumer Psychology*, 28(3):497–516, 2018.

* Galperin, Andrew, and Martie G. Haselton. “Error Management and the Evolution of Cognitive Bias.” In *Social Thinking and Interpersonal Behavior*, pages 45–63. Psychology Press, 2012.

* Gigerenzer, Gerd, and Wolfgang Gaissmaier. “Heuristic Decision Making.” *Annual Review of Psychology*, 62:451–482, 2011.

* Hamilton, W. D. “Geometry for the Selfish Herd.” *Journal of Theoretical Biology*, 31(2):295–311, 1971.

* Haselton, Martie G., and Daniel Nettle. “The Paranoid Optimist: An Integrative Evolutionary Model of Cognitive Biases.” *Personality and Social Psychology Review*, 10(1):47–66, 2006.

* Haselton, Martie G., Daniel Nettle, and Paul W. Andrews. “The Evolution of Cognitive Bias.” *The Handbook of Evolutionary Psychology*, pages 724–746, 2015.

* Henrich, Joe, and Robert Boyd. “The Evolution of Conformist Transmission and the Emergence of Between-Group Differences.” *Evolution and Human Behavior*, 19(4):215–241, 1998.

* Johnson, Dominic D. P., Daniel T. Blumstein, James H. Fowler, and Martie G. Haselton. “The Evolution of Error: Error Management, Cognitive Constraints, and Adaptive Decision-Making Biases.” *Trends in Ecology & Evolution*, 28(8):474–481, 2013.

* Johnson, Dominic D. P., and James H. Fowler. “The Evolution of Overconfidence.” *Nature*, 477(7364):317–320, 2011.

* Kahneman, Daniel. *Thinking, Fast and Slow*. Penguin Books, 2012.

* Kahneman, Daniel, Jack L. Knetsch, and Richard H. Thaler. “Anomalies: The Endowment Effect, Loss Aversion, and Status Quo Bias.” *Journal of Economic Perspectives*, 5(1):193–206, 1991.

* Kakinohana, Regis K., and Ronaldo Pilati. “Differences in Decisions Affected by Cognitive Biases: Examining Human Values, Need for Cognition, and Numeracy.” *Psicologia: Reflexão e Crítica*, 36(1):26, 2023.

* Kameda, Tatsuya, Masanori Takezawa, and Reid Hastie. “The Logic of Social Sharing: An Evolutionary Game Analysis of Adaptive Norm Development.” *Personality and Social Psychology Review*, 7(1):2–19, 2003.

* Knyazev, Norman, and Harrie Oosterhuis. “The Bandwagon Effect: Not Just Another Bias.” In *Proceedings of the 2022 ACM SIGIR International Conference on Theory of Information Retrieval*, pages 243–253, 2022.

* Korteling, Johan E., and Alexander Toet. “Cognitive Biases.” *Encyclopedia of Behavioral Neuroscience*, 3:610–619, 2020.

* Korteling, J. E., J. Sassen-van Meer, A. Toet, and H. J. H. C. van Veen. “Neuro-evolutionary Framework for Cognitive Biases.” *Rapport TNO*, R10611, 2020.

* Mesa Project Contributors. *Mesa: Agent-Based Modeling in Python 3+*. GitHub repository, 2025. https://github.com/mesa/mesa

* Moore, Don A., and Paul J. Healy. “The Trouble with Overconfidence.” *Psychological Review*, 115(2):502, 2008.

* Peters, Uwe. “What Is the Function of Confirmation Bias?” *Erkenntnis*, 87(3):1351–1376, 2022.

* Queller, David C. “A General Model for Kin Selection.” *Evolution*, 46(2):376–380, 1992.

* Taylor, Shelley E., and Jonathon D. Brown. “Illusion and Well-Being: A Social Psychological Perspective on Mental Health.” *Psychological Bulletin*, 103(2):193, 1988.

* ter Hoeven, Ewout, Jan Kwakkel, Vincent Hess, Thomas Pike, Boyu Wang, rht, and Jackie Kazil. “Mesa 3: Agent-Based Modeling with Python in 2025.” *Journal of Open Source Software*, 10(107):7668, 2025. Použitá verzia softvéru: 3.3.1.

* Todd, Peter M., Ralph Hertwig, and Ulrich Hoffrage. “Evolutionary Cognitive Psychology.” *The Handbook of Evolutionary Psychology*, pages 776–802, 2015.

* Tversky, Amos, and Daniel Kahneman. “Judgment under Uncertainty: Heuristics and Biases.” *Science*, 185(4157):1124–1131, 1974.

* Van Eyghen, Hans. “Cognitive Bias: Phylogenesis or Ontogenesis?” *Frontiers in Psychology*, 13:892829, 2022.


Sushil Bikhchandani, David Hirshleifer, and Ivo Welch. A theory of fads, fashion, custom, and cultural change as informational cascades. Journal of political Economy, 100(5):992–1026, 1992.

Hershey H Friedman. Cognitive biases and their influence on critical thinking and scientific reasoning: A practical guide for students and teachers. Available at SSRN 2958800, 2023.

David Gal and Derek D Rucker. The loss of loss aversion: Will it loom larger than its gain? Journal of Consumer Psychology, 28(3):497–516, 2018.

Andrew Galperin and Martie G Haselton. Error management and the evolution of cognitive bias. In Social thinking and interpersonal behavior, pages 45–63. Psychology Press, 2012.

Gerd Gigerenzer and Wolfgang Gaissmaier. Heuristic decision making. Annual review of psychology, 62(2011):451–482, 2011.

WD HAMILTON. Geometry for the selfish herd. Journal of theoretical Biology, 31(2):295–311, 1971.

Martie G Haselton and Daniel Nettle. The paranoid optimist: An integrative evolutionary model of cognitive biases. Personality and social psychology Review, 10(1):47–66, 2006.

Martie G Haselton, Daniel Nettle, and Paul W Andrews. The evolution of cognitive bias. The handbook of evolutionary psychology, pages 724–746, 2015.

Joe Henrich and Robert Boyd. The evolution of conformist transmission and the emergence of between-group differences. Evolution and human behavior, 19(4):215–241, 1998.

Dominic DP Johnson, Daniel T Blumstein, James H Fowler, and Martie G Haselton. The evolution of error: Error management, cognitive constraints, and adaptive decision-making biases. Trends in ecology & evolution, 28(8):474–481, 2013.

Dominic DP Johnson and James H Fowler. The evolution of overconfidence. Nature, 477(7364):317–320, 2011.

Daniel Kahneman. Thinking Fast and Slow. Penguin Books, 2012.

Daniel Kahneman, Jack L Knetsch, and Richard H Thaler. Anomalies: The endowment effect, loss aversion, and status quo bias. Journal of Economic perspectives, 5(1):193–206, 1991.

Regis K Kakinohana and Ronaldo Pilati. Differences in decisions affected by cognitive biases: examining human values, need for cognition, and numeracy. Psicologia: Reflexão e Crítica, 36(1):26, 2023.

Norman Knyazev and Harrie Oosterhuis. The bandwagon effect: Not just another bias. In Proceedings of the 2022 ACM SIGIR International Conference on Theory of Information Retrieval, pages 243–253, 2022.

JE Korteling, J Sassen-van Meer, A Toet, and HJHC van Veen. Neuro-evolutionary framework for cognitive biases. Rapport TNO, page R10611, 2020.

Don A Moore and Paul J Healy. The trouble with overconfidence. Psychological review, 115(2):502, 2008.

Uwe Peters. What is the function of confirmation bias? Erkenntnis, 87(3):1351–1376, 2022.

Project Mesa Contributors. Mesa: Agent-based modeling in python 3+. https://github.com/mesa/mesa, 2025.

David C Queller. A general model for kin selection. Evolution, 46(2):376–380, 1992.

Shelley E Taylor and Jonathon D Brown. Illusion and well-being: a social psychological perspective on mental health. Psychological bulletin, 103(2):193, 1988.

Ewout ter Hoeven, Jan Kwakkel, Vincent Hess, Thomas Pike, Boyu Wang, rht, and Jackie Kazil. Mesa 3: Agent-based modeling with Python in 2025. Journal of Open Source Software, 10(107):7668, 2025. Použitá verzia softvéru: 3.3.1.

Peter M Todd, Ralph Hertwig, and Ulrich Hoffrage. Evolutionary cognitive psychology. The handbook of evolutionary psychology, pages 776–802, 2015.

Amos Tversky and Daniel Kahneman. Judgment under uncertainty: Heuristics and biases: Biases in judgments reveal some heuristics of thinking under uncertainty. science, 185(4157):1124–1131, 1974.

Hans Van Eyghen. Cognitive bias: Phylogenesis or ontogenesis? Frontiers in Psychology, 13:892829, 2022.
