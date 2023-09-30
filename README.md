# Film Corpus 2.0

This page was migrated from https://nlds.soe.ucsc.edu/fc2. Please contact me to download the raw film corpus (159MB) or the separated scenes and dialogs (131MB).

**If you use this data in your research, please refer to citation information in [Film Corpus 1.0](https://github.com/zhichaohu/film-corpus-1/tree/main).**

## Overview
This corpus is an updated version of the Film Corpus 1.0. It contains complete texts for the scripts of 1068 films in txt files, scraped from imsdb.com on Nov, 2015 using scrapy. It also contains 960 film scripts where the dialog in the film has been separated from the scene descriptions.

## Data
Film scripts are classified by genre,  but one film can be in multiple genres. There are fewer than 1068 separated scripts because we use our own script to automatically separate the dialog and scene descriptions. The distribution of the corpus by genre is: 

| Genre	| Number of films |
| ----------- | ----------- |
| Action	| 290 |
| Adventure 	| 166  |
| Animation 	| 35  |
| Biography 	| 3  |
| Comedy 	| 347  |
| Crime 	| 201  |
| Drama 	| 579  |
| Family 	| 39  |
| Fantasy 	| 113  |
| Film-Noir 	| 4  |
| History 	| 3  |
| Horror 	| 149  |
| Music 	| 5  |
| Musical 	| 22 | 
| Mystery 	| 107  |
| Romance 	| 192  |
| Sci-Fi 	| 155  |
| Short 	| 3  |
| Sport 	| 2  |
| Thriller 	| 373 | 
| War 	| 26  |
| Western 	| 13 | 
 

## Works that use this corpus

* The scene descriptions have been used to infer pairs of contingent/causal events in different genres, as described in: Hu, Zhichao, Elahe Rahimtoroghi, Larissa Munishkina, Reid Swanson, and Marilyn A. Walker. "[Unsupervised Induction of Contingent Event Pairs from Film Scenes](https://www.researchgate.net/profile/Marilyn_Walker2/publication/256695472_Unsupervised_Induction_of_Contingent_Event_Pairs_from_Film_Scenes/links/00b7d5239f6966d083000000.pdf)." In Conference on Empirical Methods in Natural Language Processing (EMNLP), Seattle, Washington, USA, 2013.
* Dialogue has been used for developing statistical stylistic character models as described in: Walker, Marilyn A., Ricky Grant, Jennifer Sawyer, Grace I. Lin, Noah Wardrip-Fruin, and Michael Buell. "[Perceived or Not Perceived: Film Character Models for Expressive NLG](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.380.9026&rep=rep1&type=pdf)." In International Conference on Interactive Digital Storytelling (ICIDS), Vancouver, Canada, 2011. BEST PAPER AWARD.
* Grace I. Lin and Marilyn A.Walker. "[All the World's a Stage: Learning Character Models from Film](http://www.aaai.org/ocs/index.php/AIIDE/AIIDE11/paper/viewFile/4065/4411&embedded=true)." In Proceedings of the Conference on Artificial Intelligence and Interactive Digital Entertainment (AIIDE), Stanford, California, USA, 2011. BEST STUDENT PAPER AWARD.
