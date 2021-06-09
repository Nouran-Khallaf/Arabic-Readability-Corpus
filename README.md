# Arabic Readability [CEFR](https://www.coe.int/en/web/common-european-framework-reference-languages/level-descriptions) Classified sentences:
## Corpus description
This corpus was originally built for Arabic sentence difficulty classification by compiling a corpus from Three available source classified for readability on the document level [Gloss, ALC(Arabic Learner Corpus), Al-Kitaab fii TaAallum al-Arabiyya]along with a large Arabic corpus obtained by Web crawling. As these corpora have been annotated on the document level and not on the sentence level, we assigned each sentence to the document level in which it appears, by using several filtering heuristics, such as sentence length and containment, as well as via re-annotation through machine learning, and dataset cleaning procedures. All corpora are described in the following section except for Al-Kitaab fii TaAallum al-Arabiyya due to copyright restriction it is not available as a part of this resource.

### Gloss Corpus 
- The first corpus source is the reading section of the [Gloss Corpus](https://gloss.dliflc.edu/)  developed by the Defense Language Institute (DLI).
- Texts in Gloss have been annotated on a six level scale of the Inter-Agency Language Roundtable (IL ), which has been matched to the CEFR levels according to  [Transfer schema](https://www.actfl.org/sites/default/files/reports/Assigning_CEFR_Ratings_To_ACTFL_Assessments.pdf). 
- Gloss is divided according to the four competence areas (lexical, structural, socio-cultural and discursive) and ten different genres (culture, economy, politics, environment, geography, military, politics, science, security, society, and technology). 

### ALC [Arabic Learner Corpus]
- The second corpus source is the [ALC](https://www.arabiclearnercorpus.com/about-the-corpus-en) , which consists of Arabic written text produced by learners of Arabic in Saudi Arabia collected by [Alfaifi and Atwell, 2013](https://www.researchgate.net/publication/267600799_Arabic_Learner_Corpus_v1_A_New_Resource_for_Arabic_Language_Research). 
- Each text file is annotated with a proficiency level of the student. We mapped these student proficiency levels to CEFR levels.

### Web Corpus
- A counterpart corpus of texts not produced for language learners in mind is provided by I-AR
- 75,630 Arabic web pages collected by wide crawling [Sharoff, 2006](http://corpus.leeds.ac.uk/serge/publications/2006-ijcl-proof.pdf). 
- A random snapshot of approximate  8000 sentences longer than 15 words was used to extend the limitations of C-level sentences coming from corpora for language learners.


## Data Distribution

The following Table  shows distribution of the number of used sentences and tokens per each Common European Framework of language proficiency Reference [CEFR](https://www.coe.int/en/web/common-european-framework-reference-languages/level-descriptions). In principle we have data for 7-way (A1.1,A1.2, A2, B1.1, B1.2, B2, C),  5-way (A1,A2,B1,B2,C), and 3-way (A, B or C) and binary (A+B vs C) classification tasks.

| CEFR-Top |CEFR-Sub | ALC  | Gloss  |Web  | Total Sentence
|:---:|:---:|:---:|:---:|:---:|:---:|
| A| A1.1 |2465  | 419 |-  |7390|
|  | A1.2| 1380 | 189 |  -||
|  | A2 | 2258 | 697 | - ||
| B | B1.1 | 2501 | 449 |-  |3939|
|  | B1.2 | 113 | 876 | - ||
|  | B2 |  100| 117 |-  ||
|  C| C | 173 | - |8414  |8587|


## How to use
- you can use these corpora separate or combined as represented in files, also you may use the data as seven or five or three or binary CEFR levels.
- according to our experiments we recommend combining A2 level with B level if used for sentence readability classification.


_If you use any of these corpora in your work, please cite this paper:_

```

@inproceedings{khallaf-sharoff-2021-automatic,
    title = "Automatic Difficulty Classification of {A}rabic Sentences",
    author = "Khallaf, Nouran  and Sharoff, Serge",
    booktitle = "Proceedings of the Sixth Arabic Natural Language Processing Workshop",
    month = apr,
    year = "2021",
    address = "Kyiv, Ukraine (Virtual)",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2021.wanlp-1.11",
    pages = "105--114",
}
```
