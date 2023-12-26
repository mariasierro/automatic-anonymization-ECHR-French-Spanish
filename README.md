This repository contains all the corpora of case reports from the European Court of Human Rights (ECHR) in French and Spanish that were built and annotated for anonymization as part of the work presented in the Master's thesis "Automatic anonymization of legal texts from the European Court of Human Rights: building four corpora of case reports in French and Spanish language for anonymization".

As it is mentioned in the thesis, the corpora differ on the annotation procedure: some corpora were annotated by automatically projecting the annotations of the English corpus built by Pilán et al. (2022), and the other corpora were manually annotated by following a reinterpretation of their guidelines.

The files with the name ...-sents-number.tsv have the exact same content as the other files, but here the sentences are numbered in order to facilitate the assessment of the mBERT model.

In addition to that, this repository contains several Jupyter Notebooks. These notebooks display the experiments that were carried out for assessing Flair and mBERT on a Named Entity Recognition (NER) task employing the newly-built corpora.

References

Pilán, I., Lison, P., Ovrelid, L., Papadopoulou, A., Sánchez, D. & Batet, M. (2022). The Text Anonymization Benchmark (TAB): A Dedicated Corpus and Evaluation Framework for Text Anonymization. In Computational Linguistics, 48(4), pp. 1053–1101. Cambridge, MA: MIT Press. doi: 10.1162/coli_a_00458.
