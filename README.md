# ABBYY Compreno Semantic Hierarchy (simplified)

<a href="https://creativecommons.org/licenses/by-nc/4.0/"><img src="https://img.shields.io/static/v1?label=license&message=CC-BY-NC-4.0&color=green"/></a>

Here we present the materials for the semantic analysis of texts in natural languages based on the ABBYY Compreno linguistic technologies.

ABBYY decided to publish this technology for the needs of the scientific society in the area of corpus linguistics under terms of the CC-BY-NC 4.0 License. 

 The ABBYY Compreno model consists of morphological, syntactic and semantic patterns and includes the syntactic and semantic parser built on them.

The core of the model is the ABBYY Compreno Semantic Hierarchy - the thesaurus-like semantic tree, which consists of the semantic classes (SCs). SCs correspond to semantic fields universal for all languages included in the hierarchy and denote semantic senses common for all languages. The SCs are filled with lexical contents (lexical classes, or LCs) special for each language of the hierarchy.

The ABBYY Compreno Semantic Hierarchy serves the basis for the ABBYY Compreno markup format. The markup includes the boundaries of the constituents, the SC for every token and the semantic relations between all the constituents (semantic roles, or, deep slots). Additionally, the markup can also be provided with surface, or syntactic, roles, coreference, non-tree links, and some other information.

In the current repository, we suggest a shortened version of the hierarchy, where one can see only the hyperonym SCs. The hierarchy is presented in the form a .csv table which contains the information needed to visually re-create the Semantic Hierarchy as a tree for exploration.

Moreover, we suggest a 400 000 token [dataset](https://github.com/compreno-semantics/compreno-corpus) provided with the generalized version of the semantic markup, which includes the boundaries of the constituents, the generalized SCs and the generalized semantic roles between the constituents.
