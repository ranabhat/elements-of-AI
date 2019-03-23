
# Key Terminology

#### Chapter 1
---------------

> 1. **Autonomy**: The ability to perform tasks in complex environments without constant guidance of a user.
> 2. **Adaptivity**: The ability to improve performance by learning from experience.
> 3. **Machine learning**: Systems that improve their performance in a given task with more and more experince or data.
> 4. **General vs narrow AI**: Narrow AI refers to AI that handles one task. General AI, or Artificial General Intelligence (AGI)refers to a machine that can handle any intellectual task. All the AI methods we use today fall under narrow AI, with general AI being in the realm of science fiction.
> 5. **Strong vs weak AI**: Strong AI would amount to a "mind" that is genuinely intelligent and self-conscious. Weak AI exhibit intelligent behaviors despite being *mere* computers.

#### Chapter 2
---------------

> 1. **The state space**: means the set of possible situations. In the chicken-solving, the state space consisted of ten allowed states NNNN thru' to FFFF (but not for example NFFF, which the puzzle rules don't allow). If the task is to navigate from place A to place B, the state space could be the set of locations defines by their (x,y) coordinates that can be reached from the startong point A. Or we could use a constrained set of locations, for example, different street addresses so that the number of possible states is limited.
> 2. **Transitions**: are possible moves between one state and another, such as NNNN to FNFN. It is important to note that we only count direct transitions that can be accomplished with a single action as transitions. A sequence of multiple transitions, for example, from A to C, from C to D, and from D to B (the goal), is a path rather than a transition.
> 3. **Costs**: refers to the fact that, oftentimes the different transitions aren't all like. They can differe in ways that make some transitions more preferable or cheaper (in a not necessarily monetary sense of the word) and others more costly. We can express this by associating with each transition a certain cost. If the goal is to minimize the total distance traveled, then a natural cost is the geographical distance between states. On the other hand, the goal could actually be to minimize the time instead of the distance, in which case the natural cost would obviously be the time. If all the transitions are equal, then we can ignore the costs.

#### Chapter 3
---------------

> 1. **Prior and posterior odds**: The Bayes rule can be expressed in many forms. The simplest one is in terms of odds. The idea is to take the odds for something happening (against it not happening), which we'll write as prior odds. The word prior refers to our assessment of the odds before obtaining some new information that may be relevant. The purpose of the formula is to update the prior odds when new information becomes available, to obtain the posterior odds, or the odds after obtaining the information (the dictionary meaning of posterior is "something that comes after, later.")
> 2. **Likelihood ratio**: is the probability of the observation in case the event of interest, divided by the probability of the observation in case of no event.