# Word-Meaning-Comparison-using-SOTA-models

Words often have multiple meanings associated with them and the surrounding context often
determines the specific meaning of the word which is used. The goal of this assignment is to
develop deep neural models that can identify whether a particular word used in a sentence pair
has the same meaning in both sentences or has a different meaning in each of the sentences.

For example,
S1: We often used to play on the bank of the river
S2: We lived along the bank of the Ganges.
S3: He cashed a check at the bank
S1 and S2 use the same meaning of the word bank (river bed) while S1 and S3 use different
meanings of the word bank (river bed vs. financial institution)

We call this task Word Meaning Comparison and frame it as a classification problem. The NLP
model must classify the input sentence pair (X) and the word (W) into a label T if W has the
same meaning in both sentences of X and F if W has different meanings.

the pretrained models you can use to the following four: 
1. bert-base-(cased/uncased)
2. DistilBERT
3. alberta-xlarge 
4. T5v1.1-small

Popular HuggingFace library is user for this task.
