#    SpanishGLUE: 
## A Natural Language Understanding Benchmark for Spanish   




Natural Language Understanding (NLU) technology has improved significantly over the last few years, 
and multitaskbenchmarks such as GLUE are key to evaluate this improvement in a robust and general way. 
These benchmarks take into account a wide and diverse set of NLU tasks that require some form of 
language understanding, beyond the detection of superficial, textual clues. However, they are costly 
to develop and language-dependent, and therefore they are only available for a small number of languages. 

We present SpanishGLUE, a new NLU benchmark for Spanish, which has been elaborated from previously 
existing datasets and following similar criteria to those used for the construction of GLUE and SuperGLUE. 
SpanishGLUE is composed of several well known datasets, its with its own license.



The 7 tasks included in SpanishGLUE:

| Dataset        |\|Train\||\|Val\| |\|Test\|| Task                   | Metric | Domain          |
|----------------|--------:|-------:|-------:|------------------------|--------|-----------------|
| NERCconll2002  |   8,324 |  1,916 |  1,518 | NERC                   | F1     | News            |
| FMTODes_intent |   3,417 |  1,900 |  1,348 | Intent classification  | F1     | Dialog system   |
| FMTODes_slot   |  29,471 | 16,252 | 11,695 | Slot filling           | F1     | Dialog system   |
| MLDoc          |   9,458 |  1,000 |  4,000 | Topic classification   | F1     | News            |
| InterTass2020  |   4,802 |  2,465 |  1,500 | Sentiment analysis     | MF1    | Twitter         |
| XNLIes         | 392,702 |  2,490 |  5,010 | NLI                    | Acc    | Wikipedia       |
| SQAC           |  15,036 |  1,864 |  1,910 | QA (QNLI)              | Acc    | Wikipedia       |


Acc refers to accuracy, F1 refers to micro-average F1-score, and MF1 refers to macro-average F1-score.


For more details, each dataset is provided with their corresponding README file.

Note: the train file for XNLIes needs to be uncompressed.

Licensing
-------------

Each dataset of the SpanishGLUE benchmark has it's own license (due to most of them being or 
being derived from already existing datasets), available in their respective README file. 

But, here we provide a brief summary of them:


| Dataset        | License                             |
|----------------|-------------------------------------|
| NERCconll2002  |                     Unknown         |
| FMTODes_intent |                     CC BY-NC-SA 4.0 |
| FMTODes_slot   |                     CC BY-NC-SA 4.0 |
| MLDoc          |    CC BY-NC  4.0 + NIST agreement*  |
| InterTass2020  |                     Unknown         |
| XNLIes         |                     OANC*           |
| SQAC           |                     CC BY-SA    4.0 |


* OANC license (Open American National Corpus license): https://www.anc.org/OANC/license.txt

* To access to MLDoc dataset, a NIST agreement must be signed with Reuters. More info at https://github.com/facebookresearch/MLDoc

For the rest of the files of the benchmark applies the following lisense.

Copyright (C) by Elhuyar Foundation. 
This benchmark and evaluation scripts are licensed under the Creative Commons Attribution 4.0
International License (CC BY 4.0). To view a copy of this license, visit 
http://creativecommons.org/licenses/by/4.0/.






Contact information
-----------------------
Gorka Urbizu, Iñaki San Vicente: {g.urbizu,i.sanvicente}@elhuyar.eus
