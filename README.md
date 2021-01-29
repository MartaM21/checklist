# CheckList with SentiWordNet
This repository contains the forked code of CheckList.

References: 
>[Beyond Accuracy: Behavioral Testing of NLP models with CheckList](http://homes.cs.washington.edu/~marcotcr/acl20_checklist.pdf)  
> Marco Tulio Ribeiro, Tongshuang Wu, Carlos Guestrin, Sameer Singh
> Association for Computational Linguistics (ACL), 2020

Bibtex for citations:
```bibtex
 @inproceedings{checklist:acl20},  
 author = {Marco Tulio Ribeiro and Tongshuang Wu and Carlos Guestrin and Sameer Singh},  
 title = {Beyond Accuracy: Behavioral Testing of NLP models with CheckList},  
 booktitle = {Association for Computational Linguistics (ACL)},  
 year = {2020}  
```

## Using SentiWordNet 
```
editor.neutral('The girl see', 'girl')
```

> 
["('daughter.n.01') Pos: 0.0 Neg: 0.0 Obj: 1.0",

 "('girl.n.05') Pos: 0.0 Neg: 0.0 Obj: 1.0",
 
 "('girlfriend.n.02') Pos: 0.0 Neg: 0.0 Obj: 1.0",
 
 "('girl.n.01') Pos: 0.0 Neg: 0.0 Obj: 1.0"]

```
editor.positive('The girl is happy', 'happy')
```
>
["('happy.a.01') Pos: 0.875 Neg: 0.0",

"('felicitous.s.02') Pos: 0.75 Neg: 0.0",

"('glad.s.02') Pos: 0.5 Neg: 0.0"]

```
editor.negative('The girl is mad', 'mad')
```
>
["('brainsick.s.01') Pos: 0.0 Neg: 0.5"]

## API reference
On [readthedocs](https://checklist-nlp.readthedocs.io/en/latest/)

## Code of Conduct
[Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct)
