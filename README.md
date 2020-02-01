# SyntacticProcessing_NLP_HMM_Viterbi_POS_Tagging

Modify Viterbi algorithm to solve the problem of unknown words using at least two techniques.

#### Data

For this assignment, use the Treebank dataset of NLTK with the 'universal' tagset. The Universal tagset of NLTK comprises only 12 coarse tag classes as follows: Verb, Noun, Pronouns, Adjectives, Adverbs, Adpositions, Conjunctions, Determiners, Cardinal Numbers, Particles, Other/ Foreign words, Punctuations.

 

Note that using only 12 coarse classes (compared to the 46 fine classes such as NNP, VBD etc.) will make the Viterbi algorithm faster as well.

 

#### Goals

Split the Treebank dataset into train and validation sets. Use a sample size of 95:5 for training: validation sets, i.e. keep the validation size small, else the algorithm will need a very high amount of runtime.

 

Accomplish the following:

- Write the vanilla Viterbi algorithm for assigning POS tags (i.e. without dealing with unknown words)
- Solve the problem of unknown words using at least two techniques. These techniques can use any of the approaches discussed - lexicon, rule-based, probabilistic etc. Note that to implement these techniques, either write separate functions and call them from the main Viterbi algorithm, or modify the Viterbi algorithm, or both.
- Compare the tagging accuracy after making these modifications with the vanilla Viterbi algorithm.
- List down at least three cases from the sample test file (i.e. unknown word-tag pairs) which were incorrectly tagged by the original Viterbi POS tagger and got corrected after modifications.
