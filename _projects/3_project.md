---
layout: page
title: September 11
description: Exploration and Exploitation. Chess, Checkers, and Classic Board Games
img: assets/img/classic.jpg
importance: 3
related_publications: true
category: work
---

Please read BEFORE CLASS "Checkers is Solved" {% cite schaeffer2007checkers %}. I am able to access this when I am on the campus internet. Otherwise, it is behind a paywall.

Much of today's class will be focused on Symbolic, Logic-Based, or Classic AI. This was the assumption that you could represent things in a higher-level, symbolic or human-readable, format and attack problems that way. It led to many advances in AI, particularly search.

Complexity for some common games:
* Checkers Arthur Samuel. 1959. Alpha-Beta Pruning. 10^40 - 10^50 range for complexity. Solved 2007
* Chess 10^120 (Shannon number) was published in 1950. Yes, the same Shannon who we talked about for WORDLE last week. {% shannon1950xxii %}
* Connect-4. Solved independently 2 weeks apart in 1988 (James Allen 2008; {% allis1988knowledge %} . In 2008, it was shown to have 4,531,985,219,092 reachable positions  (70,728,639,995,483  had been estimated) {% edelkamp2008symbolic %}. The starting player can win.
* Othello 10^58. Solved in 2023 {% takizawa2023othello %}
* Atoms in the Universe 10^80 (very rough approximation)
* Tic-tac-toe 10^5. 9! 362,880

Chess was one of the first games to really inspire people when a computer solved it. Gary Kasparov is one of the best chess players ever. He held the highest FIDE ranking for decades. In 1997 (after having previously beaten earlier iterations of the machine, he lost to an IBM computer called Deep Bleu. He even had [a Pepsi ad](https://www.youtube.com/watch?v=cUqXr9Jlhwc)

## A Note on Compute
You have probably heard of Moore's law. Essentially, the number of transitors on a microchip roughly doubles every two years. It is tough to think about exponentials as a human. What does this mean exactly? DeepBlue had an actual 8x8 circuit to mimic a board that was custom designed. It had multiple of these strung together. In 1997, DeepBlue was the 259th most powerful super computer at 11.38 GFLOPS. Here are some other FLOP statistics:

* Apollo 11 Guidance Computer 12,250 FLOPS in 1969
* CRAY-2 Supercomputer was the fastest machine in 1985 with 1,900,000,000 FLOPS
* DeepBlue in 1997 had 11,380,000,000
* iPhone today has 2,000,000,000,000 FLOPS capabillities
