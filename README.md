# Summary

SiMoNERo is a medical corpus of contemporary Romanian.

# Introduction


SiMoNERo contains texts from three medical subdomains: cardiology, diabetes, endocrinology. The texts come from scientific books, journal articles and blog posts, but predominant are those coming from books.
The texts display the following levels of annotation: tokenization, POS tagging, lemmatization, syntactic parsing and medical Named Entities (of the following types: ANAT (body parts), CHEM (Chemicals and Drugs), DISO (disorders), and PROC (procedures)). All levels, except for the syntactic one, are hand validated. The description of the corpus creation (excluding the syntactic annotation) is presented in Mitrofan et al. (2019).
The syntactic parsing was made with the NLP Cube (https://github.com/adobe/NLP-Cube) system.

# Basic Statistics
Tree count: 4,239
Tokens: 131,411


# Acknowledgments

We are grateful to the following texts providers: http://federatiaromanadiabet.ro (accessed November 2016), https://rmj.com.ro/ (accessed November 2016), https://societate-diabet.ro/ (accessed November 2016), http://pentrudiabet.ro (accessed November 2016).

## References

Mititelu, V.B. and Mitrofan, M., The Romanian Medical Treebank - SiMoNERo. Proceedings of the The 15th Edition of the International Conference on Linguistic Resources and Tools for Natural Language Processing – ConsILR-2020ISSN 1843-911X, p.7-16, 2020.

Maria Mitrofan, Verginica Barbu Mititelu, Grigorina Mitrofan, MoNERo: a Biomedical Gold Standard Corpus for the Romanian Language, in Proceedings of the BioNLP workshop, Florence, Italy, 1 August 2019, p. 71-79, Association for Computational Linguistics (https://www.aclweb.org/anthology/W19-5008).


# Changelog

* 2019-11-15 v2.5
  * Initial release in Universal Dependencies.
* 2020-10-27 v2.7
* UD 2.5 --> 2.7
  * The number of trees was considerably increased. UD 2.5 --> 2.7
  * Increase the treebank size to 4239 sentences.
  * Removed the errors reported by the content validation tool.
  * Manual improvements of the annotation, concerning POS-tagging, syntactic labeling.
* 2021-04-30 v2.8
* UD 2.7 --> 2.8
  * Applied automatic (but manually checked) corrections as executed by [ro-ud-autocorrect](https://github.com/racai-ai/ro-ud-autocorrect).
  * Removed all artificially inserted spaces between punctuation tokens and nearby words; Regenerated the `# text =` comment accordingly.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.5
License: CC BY-SA 4.0
Includes text: yes
Genre: medical
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Mitrofan, Maria; Barbu Mititelu, Verginica
Contributing: elsewhere
Contact: maria@racai.ro, vergi@racai.ro
===============================================================================
</pre>
