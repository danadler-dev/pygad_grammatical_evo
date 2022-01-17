[Grammatical Evolution](https://link.springer.com/chapter/10.1007/978-1-4615-0447-4_4) is a form of Genetic Programming that takes a BNF grammar as an input
and generates expressions from that grammar. The genes are a vector of integers. 

The generator takes each integer in the gene, and uses it to index into the number of productions available (start is the top level production). 

It uses modulo to wrap around in case or too few/many.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15gbcwVol682QnNL3mPQYeUH2NFd5iZrt?usp=sharing)

