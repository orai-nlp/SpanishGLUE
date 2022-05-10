# QA-SQAD
## QNLI for Spanish

In order to create a NLI task on QA domain, we 
adapted the QA dataset SQAD (Carrino et al., 2020), 
a conversational Question Answering (QA) dataset 
for Spanish created by machine translation. 


We adapted this dataset into a sentence pair binary 
clas sification tasks, following the design of QNLI for
English (Wang et al., 2019). We form a pair between each
question and each sentence in the corresponding context 
and then filter out the pairs with the lowest lexical
overlap between the question and the sentence in case
of negative samples, until we are left with a balanced
dataset, formed by train, dev and test splits. As evaluation 
metric, we follow the English QNLI design and use accuracy.


Dataset format and distribution
----------------

The dataset is divided into three files: train, test and development splits:

15,036 train.tsv

1,864 dev.tsv

1,910 test.tsv

 		

Authors
-----------
Gorka Urbizu, Iñaki San Vicente and Xabier Saralegi


Affiliation of the authors: 
Elhuyar Foundation




Licensing
-------------
Copyright (C) by Elhuyar Foundation. 
This resource is distributed under the Creative Commons Attribution-ShareAlike 4.0 International Public License (CC-BY-SA). 
The full details of this license can be found at http://creativecommons.org/licenses/by/4.0/legalcode





Acknowledgements
-------------------
If you use this dataset please reference this benchmark repository for now


Contact information
-----------------------
Gorka Urbizu, Iñaki San Vicente: {g.urbizu,i.sanvicente}@elhuyar.eus




References
--------------
Carrino, C. P., Costa-jussà, M. R., & Fonollosa, J. A. (2020, May). 
Automatic Spanish Translation of SQuAD Dataset for Multi-lingual Question Answering. 
In Proceedings of the 12th Language Resources and Evaluation Conference (pp. 5515-5523).

Wang, A., Pruksachatkun, Y., Nangia, N., Singh, A., Michael, J., Hill, F., Levy, O., and Bowman, S. R. (2019). 
Superglue: A stickier benchmark forgeneral-purpose language understanding systems. CoRR, abs/1905.00537.
