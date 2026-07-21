Summary
UD_Peripheral_Mongolian-Ordos is a treebank of Ordos, a Mongolic language variety spoken in the Ordos region of Inner Mongolia, China. The treebank consists of grammatical example sentences in Latin transliteration, manually annotated according to Universal Dependencies guidelines.

Introduction
The Ordos treebank contains 80 sentences (274 tokens) of Ordos, a variety of Peripheral (Southern) Mongolian. The data consist of grammatical example sentences, some of which are drawn from Georg (2003). The sentences are presented in Latin transliteration and are accompanied by English translations.

All sentences are manually annotated with lemmas, universal part-of-speech tags (UPOS), morphological features, and dependency relations. The annotation prioritizes UD core morphological features and dependency relations. A small number of language-specific layered features (for possessive agreement) and dependency subtypes are used to capture distinctions that are morphologically or syntactically overt in Ordos. In addition, some Ordos-specific morphological categories that do not correspond to any feature in the universal inventory (namely derivational categories on numerals and focus marking) are encoded in the MISC column, in accordance with UD conventions for annotations that are not part of the universal feature inventory.

Morphological annotation

All UD core features used in the treebank take standard universal values. Two language-specific layered features are used to mark possessive agreement on nouns:

`Number[psor]` — number of the possessor (values: `Sing`, `Plur`)
`Person[psor]` — person of the possessor (values: `1`, `2`, `3`)

The following Ordos-specific morphological information is encoded in the MISC column rather than FEATS, as it does not correspond to any category in the universal feature inventory:

`Derivation=Collective` — collective derivation on numerals (e.g. *gurb.uul* 'three together')
`Derivation=Multiplicative` — multiplicative derivation on numerals (e.g. *gurban.tai* 'three times')
`Derivation=Iterative` — iterative derivation on numerals (e.g. *gurba.da* 'three times over')
`Focus=Only` — restrictive focus particle (e.g. *gurba.kan* 'only three')

Dependency annotation

UD core relations are used throughout the treebank. The following language-specific dependency subtypes are used:

`det:poss` — possessive determiner
`nmod:poss` — possessive nominal modifier
`nmod:tmod` — temporal nominal modifier
`obl:agent` — agent of a passive construction
`obl:tmod` — temporal oblique modifier

Acknowledgments

The Ordos treebank was created by Wenchao Li and Haitao Liu. The annotation of lemmas, part-of-speech tags, morphological features, and dependency relations was carried out manually according to the Universal Dependencies guidelines. Some of the example sentences are drawn from Georg (2003).

We are especially grateful to Daniel Zeman for his guidance in setting up the treebank repository and for his help with the Universal Dependencies workflow. We also thank the Universal Dependencies community for their support during the preparation and release of this treebank.

References

Georg, Stefan. 2003. Ordos. In Juha Janhunen (ed.), *The Mongolic Languages*, 193–209. London: Routledge.

Changelog

2026-11-15 v2.19
Initial release in Universal Dependencies.
 
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
