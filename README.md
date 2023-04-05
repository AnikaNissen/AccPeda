# AccPeda
## Data Analysis Files for the Paper -- From the Classroom to Journal Publication: A Guide to Publishing Accounting Pedagogy
### Authors: Samantha Taylor, Bryce Cross, Anika Nissen, Janine McGregor, Naomi Richards


In this repository, you can find the raw data that we used in our paper -> ``Exported Items_data_v2.xlsx``.


The *algorithmic preprocessing* and analysis script will contain both the code as well as comments why each step was performed and what was performed. You find these info here: ``AccPeda - LDA Analysis_v2.ipynb``.

The *manual classification* of each paper was performed by Samantha Taylor and Bryce Cross first independently from each other, and then both of them compared each category and decided on a primary, and a set of secondary categories for each paper. The manual classification results are also included in our final results sheet -> ``Results/AccPedagogy_Topics_FinalResults.xlsx``.


From our analyses, we generated the following outputs that can be found in this respository:

* ``LDA_VIS_AccPedagogy_v3.html`` which contain a graphical, interactive figure to explore the identified topics from the literature
* ``Results/Top20-Bigrams.png`` and ``Results/Top20-Trigrams.png`` visualized the top 20 bigrams and trigrams respectively, that were identified in the abstracts of the papers
* ``Results/AccPedagogy_Topics_FinalResults.xlsx`` is the final *master* results sheet that contains the main bibliometric info of the anayzed papers, the probability of each paper for each LDA topic, the LDA topic selected with the highest probability each, as well as the manual classification result 
