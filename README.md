# llama4
#qwen

LLM predict the next word based on higher probability percentage.

Greedy Sampling : pick the highest probability words

Top-K Sampling : top most k  likely words

Random Sampling :

*Temperature Sampling: important in coding and math queries

Token

Computational Cost:
    "The quick brown fox jumps over the lazy dog."
        > Letter Tokenizer : 44 tokens = 44 * compute
        > Word Tokenizer   : 9 tokens = 9 * compute
        > Sentence Tokenizer: 1 token = 1 * compute

massive vocabulary

Quick note : there might be breakthrough in the future that make word or sentence level tokens the best options, research in this field is very fast and accelarating.


Subword tokens:
    Require less computation then processing each letter separately
    vocabulary size reduced from 10s of millions to just 100s of thousands
    better at undestanding text with spelling mistakes

vovab : {
    "sh": 927,
    "ual": 928,
    "Type": 929,
    "son": 930,
    "new": 931,
    "Ġag": 933,
    "ern": 932,
    "AR": 934,
}
Tokens on the left paired with a numbers from 0 to 151664 on the right.
    > vocabulary contains 151665 tokens.
    > each token is indexed with a number.

Vector embeddings : array of numbers

Each token have thier vector embedding array:
    "car" : [0.23, 0.3321,-0.3112,0.61901511
    






