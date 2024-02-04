This repository contains the corpora of case reports from the [European Court of Human Rights (ECHR)](https://hudoc.echr.coe.int/#{%22documentcollectionid2%22:[%22GRANDCHAMBER%22,%22CHAMBER%22]}) in French and Spanish that were built and annotated for anonymization as part of the work presented in the Master's thesis "Automatic anonymization of case reports from the ECHR in Spanish and French: evaluation of two different annotation approaches". In addition to that, this repository contains several Jupyter Notebooks. These notebooks display the experiments that were carried out for assessing Flair on a Named Entity Recognition (NER) task employing the newly-built corpora. Moreover, the file "testing_flair_models.ipynb" displays a test of the models resulting from the aforementioned experiments on new made-up sentences for a quality assessment.

The different corpora and the notebooks with the experiments are divided in different branches:

- The branch "whole-corpora-(127-texts)" focuses on the Spanish and French corpora of 127 case reports per language that were annotated by automatically projecting the annotations of the test set of the English corpus built by Pilán et al. (2022). The NER models that resulted from the experiments on these corpora are available on Huggingface: mariasierro/flair-ner-echr-es-projected and mariasierro/flair-ner-echr-fr-projected.

- The branch "corpora-projected-reviewed-annots" focuses on the subsets of the aforementioned corpora containing the texts whose annotations were projected and subsequently reviewed by human reviewers. The NER models that resulted from the experiments on these subsets of the corpora are available on Huggingface: mariasierro/flair-ner-echr-es-rev and mariasierro/flair-ner-echr-fr-rev.

- The branch "corpora-manual-annots" contains the subsets of the Spanish and French corpora (parallel to subsets of the corpora included in the branch "corpora-projected-reviewed-annots") that differ on the annotation procedure: these subsets of the corpora (one per language) were manually annotated by following a reinterpretation of Pilán et al. (ibid) guidelines. The NER models that resulted from the experiments on these subsets of the corpora are available on Huggingface: mariasierro/flair-ner-echr-es-manual and mariasierro/flair-ner-echr-fr-manual.

References

Pilán, I., Lison, P., Ovrelid, L., Papadopoulou, A., Sánchez, D. & Batet, M. (2022). The Text Anonymization Benchmark (TAB): A Dedicated Corpus and Evaluation Framework for Text Anonymization. In Computational Linguistics, 48(4), pp. 1053–1101. Cambridge, MA: MIT Press. doi: 10.1162/coli_a_00458.

