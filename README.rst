Tensorflow(0.10.0) implementation of 'Bi-directional NarytreeLSTM'.

----------------
Pre-preparation:
----------------

Download Standford Sentiment Treebank data, preprocess, and set data path './project_data/sst/'

----------------
Run:
----------------
::

    python tf_sentimentmain.py


----------------
Result:
----------------
::

    epoch 0
    avg loss 15.6715t example 6919 of 6920
    dev-scoer 0.841743119266
    time per epochis 479.233663082
    epoch 1
    avg loss 9.89021 example 6919 of 6920
    dev-scoer 0.850917431193
    time per epochis 958.180022955
    ......

----------------
Reference:
----------------

https://github.com/sapruash/RecursiveNN

Tai K S, Socher R, Manning C D. Improved Semantic Representations From Tree-Structured Long Short-Term Memory Networks[J]. Computer Science, 2015, 5(1):: 36.

Teng Z, Zhang Y. Bidirectional Tree-Structured LSTM with Head Lexicalization[J]. 2016.




