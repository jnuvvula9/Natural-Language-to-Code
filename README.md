# Natural-Language-to-Code
Use of Transformer Architecture to convert Natural Language prompt to Python Code

Code generation transformers that are pre-trained on large corpora of programs have shown great success in translating natural language to code.
Although these models do not explicitly incorporate program semantics during training, they are able to create valid code snippets for many problems. 
In this project, we experiment on the translation potential of transformers and pre-trained transformers (CodeT5) in converting human languages 
to python source code and gather results using BLEU evaluation. An analysis is presented to depict the outcomes of both methods. In conclusion, we observe
a huge performance difference between the two models, with CodeT5 outperforming the base transformer and conventional recurrent based architectures by a BLEU score of 49.06
