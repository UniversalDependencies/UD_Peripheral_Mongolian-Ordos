# Summary

UD_Peripheral_Mongolian-Ordos is a treebank of Ordos, a Mongolic language
variety spoken in the Ordos region of Inner Mongolia, China. The treebank
consists of grammatical example sentences in Latin transliteration, manually
annotated according to Universal Dependencies guidelines.

# Introduction

The Ordos treebank contains 93 sentences (335 tokens) of Ordos, a variety of
Peripheral (Southern) Mongolian. The data consist of grammatical example
sentences, some of which are drawn from Georg (2003). The sentences are
presented in Latin transliteration and are accompanied by English
translations.

All sentences are manually annotated with lemmas, universal part-of-speech
tags (UPOS), morphological features, and dependency relations. The annotation
prioritizes UD core morphological features and dependency relations, while
introducing a small number of language-specific features and relations to
capture distinctions that are morphologically or syntactically overt in Ordos.

## Morphological annotation

UD core features account for 96.57% (733) of the feature annotations, while
language-specific features account for 3.43% (26). The language-specific
feature-value pairs used in this treebank are:

* `Derivation=Collective`
* `Derivation=Iterative`
* `Derivation=Multiplicative`
* `Focus=Only`
* `Number[psor]=1`
* `Number[psor]=Plur`
* `Number[psor]=Sing`
* `Person[psor]=1`
* `Person[psor]=2`
* `Person[psor]=3`

These features encode possessive suffixes on nouns, derivational morphology on
verbs, and focus particles in discourse. Possessive agreement
(`Person[psor]`, `Number[psor]`) is marked on the nominal head, and focus
particles (`Focus=Only`) are annotated at the clausal level.

## Dependency annotation

UD core relations account for 94.93% (318) of the dependency annotations,
while language-specific subtypes account for 5.07% (17). The
language-specific dependency relations used in this treebank are:

* `det:poss`
* `nmod:tmod`
* `obl:agent`
* `obl:comit`
* `obl:instr`
* `obl:than`
* `obl:time`
* `obl:tmod`
* `subj`

# Acknowledgments

The Ordos treebank was created by Wenchao Li and Haitao Liu. The annotation
of lemmas, part-of-speech tags, morphological features, and dependency
relations was carried out manually according to the Universal Dependencies
guidelines. Some of the example sentences are drawn from Georg (2003).

We are especially grateful to Daniel Zeman for his guidance in setting up the
treebank repository and for his help with the Universal Dependencies workflow.
We also thank the Universal Dependencies community for their support
during the preparation and release of this treebank.

## References

* Georg, Stefan. 2003. Ordos. In Juha Janhunen (ed.), *The Mongolic
  Languages*, 193–209. London: Routledge.

# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Li, Wenchao; Liu, Haitao
Contributing: here
Contact: widelia@zju.edu.cn
===============================================================================
</pre>