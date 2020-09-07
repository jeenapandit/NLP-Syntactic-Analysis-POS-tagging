## NLP-Syntactic-Analysis-POS-tagging

### HMMs and Viterbi algorithm for POS tagging-POS tagging using modified Viterbi

#### Problem Statement
The vanilla Viterbi algorithm has loss of accuracy majorly due to the fact that when the algorithm encounters an unknown word (i.e. not present in the training set, such as 'Twitter'), it assigned an incorrect tag arbitrarily. This is because, for unknown words, the emission probabilities for all candidate tags are 0, so the algorithm arbitrarily chooses (the first) tag.
In this assignment, modify the Viterbi algorithm to solve the problem of unknown words using at least two techniques. 
You need to accomplish the following in this assignment:
- Write the vanilla Viterbi algorithm for assigning POS tags (i.e. without dealing with unknown words) 
- Solve the problem of unknown words using at least two techniques. These techniques can use any of the approaches discussed in the class - lexicon, rule-based, probabilistic etc. Note that to implement these techniques, you can either write separate functions and call them from the main Viterbi algorithm, or modify the Viterbi algorithm, or both.

Compare the tagging accuracy after making these modifications with the vanilla Viterbi algorithm.
