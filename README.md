# CPTMA
This code implements constituency parse tree aggregation.

# This code implements constituency parse tree aggregation.
code: This folder contains the code that implements constituency parse tree aggregation.
sample_dataset: This folder contains 100 sentences from Penn Treebank dataset. 
This is the input for the method. Ground Truth is only used for evaluation purposes.
# Input parsers
Berkeley: The code to implement this parser can be found at https://pypi.org/project/benepar/
CoreNLP: The code to implement this parser can be found at https://stanfordnlp.github.io/CoreNLP/download.html
AllenNLP: The code to implement this parser can be found at https://github.com/allenai/allennlp
Hanlp: The code to implement this parser can be found at https://github.com/hankcs/HanLP/tree/master
# Dataset details
Penn Treebank English: The dataset can be found at https://catalog.ldc.upenn.edu/LDC99T42
Ontonotes English: The dataset can be found at https://catalog.ldc.upenn.edu/LDC2013T19
Ontonotes Chinese: The dataset can be found at https://catalog.ldc.upenn.edu/LDC2013T19
Genia dataset: The dataset can be found at https://github.com/allenai/genia-dependency-trees/tree/master/original_data
French Treebank: The dataset can be found at http://ftb.llf-paris.fr/telecharger.php?langue=en
Tiger Corpus: The dataset can be found at https://www.ims.uni-stuttgart.de/documents/ressourcen/korpora/tiger-corpus/download/start.html
# Baseline Aggregation methods
The implementation of baseline aggregation methods can be found at https://evolution.genetics.washington.edu/phylip/getme-new1.html
# Steps for code execution
# Required packages
python 3
pickle
numpy
# Execution flow
python resources.py
python medcpt.py
python evaluation.py
python print_results.py
