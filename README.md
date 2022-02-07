# Skip-Gram-implementation-from-scratch-

Project's Title: Skip Gram implementation from scratch 

Motivation: This is our Assignment for CS772: Deep Learning for NLP. The aim is to study and implement the skip gram algorithm from scratch in python. 
Cluster of “animal words”: dog","tiger","cat","elephant","horse","bear","cow","monkey","deer","snake","lion"
Cluster of “bird words”: sparrow","parrot","dove","eagle","woodpecker","crane","owl","duck","cuckoo","penguin"
Create word clusters as mentioned above. Run a concordance for obtaining the neighboring words of these words. Train a skip-gram model with these words. Collect the word representations. Ensure that “animal” words are close to other “animal” words and so are “bird” words; Inter-cluster distance should be large compared to intra-cluster distance; use cosine similarity and other cluster-quality measures.

Team Members: 
1.	Tejas Gunaghe - 213194002
2.	Tanishq Awasthi - 213190003
3.	Vaibhav Singh Panwar – 213190004

Build Status: improving the model prediction

Programming Language: Python 

Libraries/API used: Nil basic pandas and Numpy

Input File: Corpus.txt – attached with the code files. File can be downloaded from below icon.
 
Model Tuning Parameters:
1.	Learning Rate: Adaptive starting from 0.001
2.	Neuron considered in hidden layer: 30
3.	Max epochs: 1000
4.	Tolerance for stopping condition: 0.001

Note: Tuning can be done inside the skipgram class in code.



Credits: 
1.	IIT Bombay course material for CS772: DL for NLP
2.	https://www.geeksforgeeks.org

