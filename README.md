# ScrambleTests
Codebase to 
1. Train classifiers on pairs of InferSent embedded sentences to predict NLI labels
2. Test its performance on a new Scrambled dataset

##Instructions
Downloads:
1. SNLI database to Downloads/SNLI/true

toy SNLI provided, download the rest
if toy:
    DATA_PATH = './Downloads/SNLI/toy/'
else:
    DATA_PATH = './Downloads/SNLI/true/'

2. glove file to Downloads/

GLOVE_PATH = './Downloads/glove.840B.300d.txt'

3. Infersent pickled model to Downloads/

MODEL_PATH = './Downloads/infersent.allnli.pickle'

creating folders (From the home file of repo):
1. ./models/
2. ./regout/



Keeping "toy = True" in main.py should run through regression and test code.
Setting it False will run the true regressuion and take a long time, and very high memory for embeddings.

Running the full version myself right now, but issues on Sherlock.
