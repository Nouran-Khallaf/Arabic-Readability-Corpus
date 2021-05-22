# Arabic Readability [CEFR](https://www.coe.int/en/web/common-european-framework-reference-languages/level-descriptions) Classified sentences:
## Corpus discription
This corpus was originally built for Arabic sentence difficulty classification by compiling a corpus from two available source classified for readability on the document level along with a large Arabic corpus obtained by Web crawling. As these corpora have been annotated on the document level and not on the sentence level, we assigned each sentence to the document level in which it appears, by using several filtering heuristics, such as sentence length and containment, as well as via re-annotation through machine learning, and dataset cleaning procedures.

### Gloss Corpus 
- The first corpus source is the reading section of the [Gloss Corpus](https://gloss.dliflc.edu/)  developed by the Defense Language Institute (DLI).
- Texts in Gloss have been annotated on a six level scale of the Inter-Agency Language Roundtable (IL ), which has been matched to the CEFR levels according to  [Transfer schema](https://www.actfl.org/sites/default/files/reports/Assigning_CEFR_Ratings_To_ACTFL_Assessments.pdf). 
- Gloss is divided according to the four competence areas (lexical, structural, socio-cultural and discursive) and ten different genres (culture, economy, politics, environment, geography, military, politics, science, security, society, and technology). 

### ALC [Arabic Learner Corpus]
- The second corpus source is the [ALC](https://www.arabiclearnercorpus.com/about-the-corpus-en) , which consists of Arabic written text produced by learners of Arabic in Saudi Arabia collected by [Alfaifi and Atwell, 2013](https://www.researchgate.net/publication/267600799_Arabic_Learner_Corpus_v1_A_New_Resource_for_Arabic_Language_Research). 
- Each text file is annotated with a proficiency level of the student. We mapped these student proficiency levels to CEFR levels.




A counterpart corpus of texts not produced for language learners in mind is provided by I-AR, 75,630 Arabic web pages collected by wide crawling \citep{sharoff06ijcl}.  A random snapshot of 8627 sentences longer than 15 words was used to extend the limitations of C-level sentences coming from corpora for language learners.

Table ~\ref{Data-Set1} shows distribution of the number of used sentences and tokens per each Common European Framework of language proficiency Reference [CEFR] Level. In principle we have data for 5-way (A1, A2, B1, etc), 3-way (A, B or C) and binary (A+B vs C) classification tasks, but here in this presentation, we focus on the 3-way and binary (simple vs complex) classification tasks.
