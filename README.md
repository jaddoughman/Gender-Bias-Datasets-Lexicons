# Gender-Bias-Datasets-Lexicons

## Abstract
Language has a profound impact on our thoughts, perceptions, and conceptions of gender roles. Gender-inclusive language is, therefore, a key tool to promote social inclusion and contribute to achieving gender equality. Consequently, detecting and mitigating gender bias in texts is instrumental in halting its propagation and societal implications. However, there is a lack of gender bias datasets and lexicons for automating the detection of gender bias using supervised and unsupervised machine learning (ML) and natural language processing (NLP) techniques. Therefore, the main contribution of this work is to publicly provide labeled datasets and exhaustive lexicons by collecting, annotating, and augmenting relevant sentences to facilitate the detection of gender bias in English text. Towards this end, we present an updated version of our previously proposed taxonomy by re-formalizing its structure, adding a new bias type, and mapping each bias subtype to an appropriate detection methodology. The released datasets and lexicons span multiple bias subtypes including: Generic He, Generic She, Explicit Marking of Sex, and Gendered Neologisms. We leveraged the use of word embedding models to further augment the collected lexicons. The underlying motivation of our work is to enable the technical community to combat gender bias in text and halt its propagation using ML and NLP techniques.

## Gender Bias Taxonomy

| **Type** | **Subtype**                | **Example**                                                                                                        | **Implication**           |
| :------- | :------------------------- | :----------------------------------------------------------------------------------------------------------------- | :------------------------ |
|  Generic Pronouns        | Generic He                 | The client should receive his invoice in two weeks.                                                                | Biased Mental Imagery     |
|  Generic Pronouns        | Generic She                | A nurse should ensure that she gets adequate rest.                                                                 | Biased Mental Imagery     |
|  Generic Pronouns        | Gendered Generic Man       | Good teachers know how to man the classroom.                                                                       | Biased Mental Imagery     |
|  Sexism        | Hostile Sexism             | Women are incompetent at work.                                                                                     | Aggressive Behavior       |
|  Sexism       | Benevolent Sexism          | They’re probably surprised at how smart you are, for a girl.                                                       | Representational Harms    |
|  Occupational Bias        | Gendered Division of Labor | Professors are men and elementary teachers are women.                                                              | Labor Force Participation |
|  Occupational Bias        | Gendered Roles & Duties    | I’ll have my girl get you a cup of coffee.                                                                         | Labor Force Participation |
|  Exclusionary Bias        | Explicit Marking of Sex    | Chairman, Businessman, Manpower, Cameraman...                                                                      | Representational Harms    |
|  Exclusionary Bias        | Gender-based Neologisms    | Man-bread, Man-sip...                                                                                              | Representational Harms    |
|  Exclusionary Bias        | Gendered Word Ordering     | “Men and Women", “Brothers and Sisters"...                                                                         | Representational Harms    |
|  Semantics        | Metaphors                  | “Cookie": lovely woman.                                                                                            | Bias Propagation          |
|  Semantics        | Gendered Attributes        | An unmarried male (bachelor) is a “personal choice”. An unmarried female (spinster) is derogatorily an “old maid". | Bias Propagation          |
|  Semantics        | Old Sayings                | A woman’s tongue three inches long can kill a man six feet high.                                                   | Bias Propagation          |


## Citation

```
@article{doughman2022gender,
  title={Gender Bias in Text: Labeled Datasets and Lexicons},
  author={Doughman, Jad and Khreich, Wael},
  journal={arXiv preprint arXiv:2201.08675},
  year={2022}
}
```
