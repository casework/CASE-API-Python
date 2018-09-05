# Cyber-investigation Analysis Standard Expression (CASE)

_Read the [CASE Wiki tab](https://github.com/ucoProject/CASE/wiki) to learn **everything** you need to know about the Cyber-investigation Analysis Standard Expression (CASE) ontology._
_For learning about the Unified Cyber Ontology, CASE's parent, see [UCO](https://github.com/ucoProject/UCO)._

# CASE Python API

### Quickstart

1. ``` python setup.py install```
2. Import `case.py` and `NLG.py` into the file you plan to implement CASE.


### NLG.py & CASE.py

The Natural Language Glossary (NLG) is an alphabetical list of types of CASE classes (categories of CASE types).
The functions in `NLG.py` create CASE objects (instances of such types) while automatically checking ontology and type.
The API (`case.py`) could be used directly to create non-typed objects if ontology and type checking are not requirements.
However, we advise against this to maintain consistency across community usage of the ontology.


Note that different versions of the NLG exist for different realizations of the Unified Cyber Ontology.
The human legible NLG corresponding to this version of CASE (one realization of UCO) can be found here:
https://casework.github.io/case/case-v0.1.0-natural-language-glossary.html


The API wraps [RDFLib](https://rdflib.readthedocs.io/en/stable/) for a JSON-LD
schematic. This verison is only directly adoptable via Python but JSON-LD is also supported in Javascript, PHP, Ruby, Java, C#, and Go.


### Examples

The `example` folder contains a slimmed down NLG, for an understanding of some of the basic function variations that exist, as well as a template for all types of conditions checked by the NLG functions.
