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

Computers , of all types, have until very recently have had insufficient computational resources to even be seriously considered as tools to make somewhat useful forecasts of future events of this type - firstly, as the 'Universe' of data points has often been far larger than the physical memory of the machines, and the time needed for computation far longer than the machines could handle. While this sound exactly like the situation associated with breaking the Enigma codes in WWII, the important consideration not applicable in terms of event forecasting is that the Enigma intercepts _contained signal_, meaning that there was _something_ which could be extracted, and have meaning to interpret. 

With regard to games of chance, there is at first none - and this is complicated dramatically by human expectations running hard against fallacies to do with both probability and chance - and not emotionally understanding either, sadly.

## The Gambler's Fallacies
There are a considerable list of fallacies to do with gambling and forecasting 'the next event' that exist. Books have been written about them - many of them ! In all cases, the fallacy lies in the short-cut of the emotional mind triumphing over the logical rational mind - and, in fairness, money makes it worse - the desire for a natural need overrides the cool, logical consideration of the many fallacies which occur when considering whether a gambling system (aside from horse or dog racing, which has variables far beyond the consideration of simpler yet still very numerically complex mathematics). 

It would be very fair to say that the mathematical sciences of <b>statistics</b> and <b>number theory</b> both evolved out of a need to circumvent the emotional mind's inability to understand the concepts of chance & probability. Here are some of the most typical that give rise to financial ruin.

<b>The Gambler's Fallacy , or the Monte Carlo Fallacy</b>
This is the most common - its the belief that if an event has occurred <i>less frequently</i> then in the future it is 'likely' to <i>occur more frequently</i>. The reason for the fallacy comes from the inability to distinguish <i>chance</i> from <i>probability</i>. The good example is a a cubic die (or dice if a pair), which has six sides with numbers of 1 to 6 - a common statistical time since before the reign of Julius Caesar, and so millenia old. 

A perfectly weighted die has the <i>probability</i> of landing on a value of 1 to 6 for <i>any</i> given throw of the dice, on the assumption that the throws made is the same each time - in terms of force, height, rotation speed, and a set of other physical factors. The **fallacy** (for this system) is the belief that the probability will 'even out' the number returned on throws - so that (for instance) if there are 100 throws played at a Monte Carlo table where the dice have been giving 'snakeyes' (a 1 and a 1) in many sequences, that to 'even things out' over the next set of sequences, a set of 12's (a six and a six) will then fall to return the probability to an even 50:50 distribution of odds and evens. 

This fallacy is of course quickly proven - there is an almost absolute (better than 99.9%) probability that this will not take place - not matter one's feelings on the matter. Until the end of play for an evening at the gambling tables, the dice may end up in all sorts of combinations, returning _anywhere_ between 1 and 1 to 6 and 6 - and all combinations in between. Continue to bet on the basis that one 'feels the odds are going to change' is what leads to ruin - there is absolutely no proof, on experiment, to justify this belief.

**The Retrospective Gamblers Fallacy**
This relates to the Gamblers Fallacy in terms of the belief that 'Past Events allow the future to be forecast' and here we get to the modern point of view

