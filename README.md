# Assignment: CKY Parsing

## Natural Language Processing

## Name: Richard Lee

### Overview

We will be building a simple parser that is trained from the ATIS (Air Traffic Information System) portion of the Penn Treebank. The training data consists of short queries and commands spoken by users of a fake robot travel agent.

The files provided and their purpose are listed below:

    - `train.trees.pre.unk` contains the trees of the training data: binary branching trees with all words that only appear once replaced with `<unk>`  
    - `dev.strings` contains the Strings of the development data
    - `dev.trees` contains the trees of the development data
    - `test.strings` contains the Strings of the test data
    - `test.trees` contains the trees of the test data
    - `preprocess.py` contains the preprocessor
    - `postprocess.py` contains the postprocessor
    - `evalb.py` contains a script to compute the labeled precision, recall, and F1 
    - `trees.py` is used by other scripts
