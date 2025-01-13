# Data-Processing 1 - Heatmaps for forecasting evaluation
## Or : Can Artificial Neural Networks forecast Lottery Draws ?
Martin La Grange, January 2025

## The attraction of lotteries

Lotteries have been in existence since the times of the Pharoahs and the Ancient Greeks, and have a very strong attraction - the potential for a big prize, for a small amount of money spent to be added to the pool won every week.
Formats differ from country to country, and the manner in which the prize is paid also differs.

A cursory look at the mathematical odds of winning a lottery draw make it seem hopeless - somewhere between 1 in 40! to 1 in 60! (factorial - a big number) is a typical probability, multipled by the factorial of the number of balls played e.g. 5! to 7! , for different systems - making the probability of getting it correct somewhere between 1 in 40 million, to 1 in 120 million for a single line played. Throw in a large prize using one or more Powerballs, or Bonus Balls from the main draw, and the probabilities become even smaller, multiplied by the number of balls within the set being drawn from.

However, people play the lottery every week - and this is due to (in consideration) two factors : Emergent Structures, and failure to appreciate Fallacy - which is all to human, and despite giving rise to incorrect appreciation of probability and chance, has still driven mathematics and science for centuries...

**Computers and games of chance**

Practically since the invention of the abacus, the computer has been seen as a tool to defeat the vagaries of chance, particularly where gambling games with monetary prizes are concerned. There are literally centuries of myth, legend and stories about various systems - whether a mental model which allows the computation of odds to always have a winning hand at cards (sich as in the novel _Oscar and Lucinda_ by Peter Carey, 1988), to use of early mainframes to compute the fall of a roulette wheel in Monte Carlo (in downtime from its job of recovering Mercury space capsules in the 1960's movie "The Honeymoon Machine"). 

And, of course, there have been numerous instances of computers being used to actually win at gambling in casinos - which have either been successful or truly tragic in result. Needless to say much fiction and fact exists in this regard.

Computers , of all types, have until very recently have had insufficient computational resources to even be seriously considered as tools to make somewhat useful forecasts of future events of this type - firstly, as the 'Universe' of data points has often been far larger than the physical memory of the machines, and the time needed for computation far longer than the machines could handle. 

While this sounds exactly like the situation associated with breaking the Enigma codes in WWII, the important consideration not applicable in terms of event forecasting is that the Enigma intercepts _contained signal_, meaning that there was _something_ which could be extracted, and have meaning to interpret. With regard to games of chance, there is at first _none_ - and this is complicated dramatically by human expectations running hard against fallacies to do with both probability and chance - and not emotionally understanding either, sadly.

## The Gambler's Fallacies
There are a considerable list of fallacies to do with gambling and forecasting 'the next event' that exist. Books have been written about them - many of them ! In all cases, the fallacy lies in the short-cut of the emotional mind triumphing over the logical rational mind - and, in fairness, money makes it worse - the desire for a natural need overrides the cool, logical consideration of the many fallacies which occur when considering whether a gambling system (aside from horse or dog racing, which has variables far beyond the consideration of simpler yet still very numerically complex mathematics). 

It would be very fair to say that the mathematical sciences of <b>statistics</b> and <b>number theory</b> both evolved out of a need to circumvent the emotional mind's inability to understand the concepts of chance & probability. Here are some of the most typical that give rise to financial ruin.

<b>The Gambler's Fallacy , or the Monte Carlo Fallacy</b>
This is the most common - its the belief that if an event has occurred <i>less frequently</i> then in the future it is 'likely' to <i>occur more frequently</i>. The reason for the fallacy comes from the inability to distinguish <i>chance</i> from <i>probability</i>. The good example is a a cubic die (or dice if a pair), which has six sides with numbers of 1 to 6 - a common statistical time since before the reign of Julius Caesar, and so millenia old. 

A perfectly weighted die has the <i>probability</i> of landing on a value of 1 to 6 for <i>any</i> given throw of the dice, on the assumption that the throws made is the same each time - in terms of force, height, rotation speed, and a set of other physical factors. The **fallacy** (for this system) is the belief that the probability will 'even out' the number returned on throws - so that (for instance) if there are 100 throws played at a Monte Carlo table where the dice have been giving 'snakeyes' (a 1 and a 1) in many sequences, that to 'even things out' over the next 100 sequences, a set of 12's (a six and a six) will then fall to return the probability to an even 50:50 distribution of odds and evens. 

This fallacy is of course quickly proven - there is an almost absolute (better than 99.9%) probability that this will _not_ take place - not matter what one's feelings are about it. Until the end of play for an evening at the gambling tables, the dice may end up in all sorts of combinations, returning _anywhere_ between 1 and 1 to 6 and 6 - and all combinations in between, and not once 'evening the odds' of an expected outcome. Continue to bet on the basis that one 'feels the odds are going to change' is what invariably leads to ruin - there is absolutely no proof, on experiment, to justify that belief.

**The Retrospective Gamblers Fallacy**
This relates to the Gamblers Fallacy in terms of the belief that 'Past Events allow the future to be forecast' and here we get to the modern point of view with regard to Neural Networks - the hope that their dispassionate mathematical structures may detect a pattern which the human mind cannot. Unfortunately, to date, there is no system with this capacity - or at least, there is no system able to avoid this fallacy _yet_

## Emergent Neural Network forecasting - the Human Brain

Even after being educated in both the sciences and mathematics, human beings often persist in purchasing Lottery Tickets on a given week. This behaviour seems irrational, until we take some aspects of this in mind, in respect of the Lottery games themselves, and their results per week:

* Someone _always_ wins a big prize
* Despite the fact that any combination of lottery balls is theoretically as good as another, people notice _patterns_
  * These patterns are often repetitive for a single given ball, week to week - which while encouraging fallacy, is also an emergent property - _perhaps_.
  * Observation over the centuries has given rise to the _hot, cold and middle warmth_ (or occurence rate) of a given set of balls.
* There exist strategies known as _Martingales_, _Wheeling_ and _Minimum-set Combinatorics_ (in contemporary parlance) - however, financially their implementation is not minimal, reducing their attraction to the average player.

The pattern-recognition occurring in the Human mind needs to be given some consideration - the human brain consists of _billions of neurons_, with _trillions_ of axonal and dentritic connections. This remains far more complex than any computer or AI software system yet extant, including the AI systems in existence in 2025, the year of writing.

While it is true that the human mind cannot realistically forecast the next Lottery draw, it is important to note that patterns are being recognised, and acted on. Given a large enough population, and the chances of winning a large Lottery prize become less remote, given enough time. If realistically matched to the probabilities involved - sometimes every single week, keeping player interest high.

When the test system is discussed, we will return to that.

## Emergent Neural Network forecasting - Artificial Neural Networks
First programmed on smaller PC's in the 1990's when the 'Mega Threshold' was exceeded for the first time even for cheaper commercial personal computers (Units of measure - Megabyte, MegaHertz system clock, Megabit networking) , the **Artificial Neural Network** became an important tool in the sciences. However, the inherent problem at that time was data and computation - particularly in terms of ANN computational units and their parameters which were not well developed then, and data throughput - which was a full order of magnitude lower than the datasets to which these early software ANN's were being applied.

The watershed period was from 2008 - 2018, in what has been termed the 'Giga Revolution' in which computers gained three orders of magnitude in terms of their computational power from the 1990's - Clock speed in GigaHetrz, memory in GigaBytes, and Gigabit networking data speeds. This was also coupled with multi-core computing rising to more than 4 cores per CPU, with the largest today (the AMD EPYC) sporting up to 196 or more CPU units in an asymmetric array. Inexpensive CPU's e.g. the AMD Ryzen 5 , can have 12 to 16 CPU units in an assymetric array - and at clock speeds and data throughput capacity which can put to to shame Supercomputers only 2 generations in the past, in terms of flexibility and computional performance.

This has also been coupled with software libraries able to harness the computational power of the GPU (Gaming Graphics Card) computational power on vector calculations, to be used in scientific computing as well - AMD ROCm and NVidia CUDA libraries are the most commonly deployed, though not the only available.

Today, a desktop PC has the capacity to perform numerical computations with sophisticated ANN libraries and technique - We have LSTM, GRU, BiDirectional, and Attention neural networks, with more complex activation functions than the Sinusoidal TanH function that existed in the 1990's available to every interested programmer.

We also have today the tools to evaluate whether a dataset is worth putting through an ANN, to save time in terms of committing resources to attempting to forecasting next steps.

## The Test System - the New Zealand National Lottery
The NZ National Lottery is an almost ideal test system to distinguish a random from nearly-random system, for statistical evaluations

