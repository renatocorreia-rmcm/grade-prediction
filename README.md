# The search for a Model Based Grade Prediction Algorithm
Solving a ![netfliz-prize](https://en.wikipedia.org/wiki/Netflix_Prize) alike problem to predict a student grade based on its previous grades and his colleagues previous grades on miscelaneous disciplines.

## The problem

Consideer the following dataset.

It is composed of students represented as vectors, where each parameter is a grade (possibly, and frequently, a NULL value != 0)

|   student    | MD  | IP  | SD   | CAD | DS  | EDOO | CALC | ARQSO | X   | ... |
| ------------ | --- | --- | ---  | --- | --- | ---  | ---  | ---   | --- | --- |
| renato       | 8.0 | --- | 9.0  | 6.0 | 6.0 | 8.5  | 8.4  | 9.0   | --- | ... |
| jorge        | 7.1 | 10. | 8.2  | 10. | 8.0 | ---  | 9.0  | ---   | --- | ... |
| ...          | ... | ... | ...  | ... | ... | ...  | ...  | ...   | ... | ... |


We assume the grade G of a student S in the discipline D has a linear relation with all his other grades (S).

We are searching an algorithm to estipulate these relations using all other students whose G_d is not NULL.

## Similar problems
