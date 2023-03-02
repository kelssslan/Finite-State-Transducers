# Finite-State-Transducers

Course: COMP 4750 Introduction to Natural Lanuage Processing

Topics: NLP, Finite State Transducers

Professor: Dr. Harold Wareham https://www.cs.mun.ca/~harold/

A special thanks to Dr. Harold Wareham for implementing a fun and great way to learn how to clean, organize and write Finite State Transducers. And also for giving me permission to share my experience with these assignments. Dr.Wareham spent months designing these assignments and the source codes are not available. Please sent me an email klan@mun.ca if you have any questions!



Create and use finite-state transducers by performing the following tasks:


1) Read in a description of a FST stored in file filename and return a stored version of that FST.
  - The special symbol "-" will be used to denote the symbol epsilon. This is followed by one or more groups of lines, one per state, which encode the transitions going outwards from that state. 
  - In each such group, the first line gives the state number and an character indicating whether that state is ("F") or is not ("N") final and each subsequent line specifies a transition by the lower and upper symbols in that transition and the number of the state towards which that transition is directed. 
  - The states in an n-state FST will be numbered from 1 to n and state 1 is assumed to be the start state. 

2) Given two stored versions F1 and F2, create and return the FST that is F1 composed with F2.

3) reconstructUpper(l, F): Print the set of upper strings associated with lower string l by FST F.
4) reconstructLower(u, F): Print the set of lower strings associated with upper string u by FST F.


**Finite State Transducers:**

vcePlu.fst: Change a plural morpheme [s] to [z] if the final sound in a word is voiced, e.g., [podPs] becomes [podPz].

addVowPlu.fst Add a vowel [e] immediately before the final plural morpheme if the final sound in the word is a fricative, e.g., [diSPs] becomes [diSPes].
