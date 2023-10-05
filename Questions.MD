# Lab 6 Questions
## Part 1: Monte Carlo Methods

**Question 1:** Explain in your own words (2-3 sentences) how you can use *Monte Carlo Methods* to estimate the value of *pi*.  

Answer:  


**Question 2:** Describe the data which FogBugz-EBS needs to create an estimate of ship times.  

Answer:  


**Question 3:** How does randomness inform the FogBugz-EBS estimates?  

Answer:  


**Question 4:** Which parts of the estimation process for FogBugz-EBS can be done in parallel? Which parts can not be done in parallel? (This can be very high-level!)  

Answer:  


**Question 5:** Are there ways to produce the same "random" numbers when using the *rand()* function? Explain why you answered that way, and how you can (or why you can't) do it.  

Answer:  

## Part 2: Coin Flipping
**Question 6:** Compile and run the sequential coin flipping program. Run it at least three times and report your timings.  

Answer:  


**Question 7:** Compile and run the OMP parallel version of the coin-flipping program. Run it on a higher-core machine (i.e. more than 2). Run it at least 3x and report the timings.  

Answer:  

### Instructions
Be sure you carefully read and work through the various clauses on the parallel for loop! It demonstrates much of what we've been talking about in class (or will be talking about in the next few classes).

## Part 3: Roulette & Cards
Look at the parallel version of Roulette ("Parallelism to the Rescue").  
**Question 8:** Explain why *numSpins* and *myBet* can be shared.  

Answer:  

**Question 9:** Explain why *spin* and *seed* are marked as private.  

Answer:  

**Question 10:** Explain what the line *reduction(+:wins)* tells the compiler to do, and why we need it.  

Answer:  


Look carefully at the "Open MP Version" of the cards code.  
**Question 11:** Which lines of code are affected by the 'parallel for' directive? How did you determine or know that?  

Answer:  

**Question 12:** Explain why *numTests* is not included in the reduction clause, even though it's a '+=' operation.  

Answer:  

### Instructions: Skip the 'Plinko' page and the 'Exercises' page.

## Part 4: Uniquely seeded Roulette Wheel
Read the final page on unique seeds for the rand function.

**Deliverable** Modify the roulette wheel code provided to have a unique seed for each threaded operation. 



