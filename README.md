# A simple Sentence-Completion-Using-Hidden-Markov-Model

This script implements three language models to complete sentences by selecting the right word from a list. 
For this issue, look at one possible word at a time and ask the language model which phrase is most probable.

questions.txt contains a few possible words and phrases to finish. 
The word to be finished is marked "____" and the pair of possible words (e.g. weather/whether) is at the end of the line. 
The phrase does not include ":" between the contenders. The script swaps "____" with a possible term to apply a language model to a phrase.

To run the script use: Sentence_Completion_using_HMM.ipynb file and questions.txt

If you want to train your model on some other corpus insted of questions.txt, just replace the 2nd argument with path to your own corpus, also, 
if you want to test your model on some different set of sentences, just replace the 3rd arugment with the path to your sentences. 
Keep in mind to use the same pattern for the custom sentences which you want to test your model on.
