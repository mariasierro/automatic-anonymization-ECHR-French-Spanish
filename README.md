In this repository, the branch "full-corpora-(127-texts)" contains the four corpora of 127 case reports from the European Court of Human Rights (ECHR) in French and Spanish that were built and annotated for anonymization as part of the work presented in the Master's thesis "Automatic anonymization of legal texts from the European Court of Human Rights: building four corpora of case reports in French and Spanish language for anonymization". In addition to that, this repository contains several Jupyter Notebooks. These notebooks display the experiments that were carried out for assessing Flair and mBERT on a Named Entity Recognition (NER) task employing the newly-built corpora.

As it is mentioned in the thesis, the corpora differ on the annotation procedure: two corpora (one per language) were annotated by automatically projecting the annotations of the English corpus built by Pilán et al. (2022), and the other two corpora (one per language) were manually annotated by following a reinterpretation of their guidelines.

The files with the name ...-sents-number.tsv correspond to the same corpora but with numbered sentences in order to facilitate the assessment of the mBERT model.

Furthermore, the other branches ()

References

Pilán, I., Lison, P., Ovrelid, L., Papadopoulou, A., Sánchez, D. & Batet, M. (2022). The Text Anonymization Benchmark (TAB): A Dedicated Corpus and Evaluation Framework for Text Anonymization. In Computational Linguistics, 48(4), pp. 1053–1101. Cambridge, MA: MIT Press. doi: 10.1162/coli_a_00458.
