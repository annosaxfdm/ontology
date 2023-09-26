# The Anthropological Notation Ontology (ANNO)

[![build](https://github.com/annosaxfdm/ontology/actions/workflows/build.yml/badge.svg)](https://github.com/annosaxfdm/ontology/actions/workflows/build.yml)
[![SHACL status](https://github.com/annosaxfdm/ontology/actions/workflows/shacl.yml/badge.svg)](https://github.com/annosaxfdm/ontology/actions/workflows/shacl.yml)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC_BY_4.0-blue)](LICENSE)
[![DOI](https://zenodo.org/badge/473966297.svg)](https://zenodo.org/badge/latestdoi/473966297)

ANNO consists of ANNOdc (domain-core) and ANNOds (domain-specific).
ANNOdc is connected to the General Formal Ontology (GFO).

## Releases

Releases have the [calendar versioning](https://calver.org/) scheme YY.MM for short year and short month.
For example, [23.08](https://github.com/annosaxfdm/ontology/releases/tag/23.08) is the state of August, 2023 and contains the ontology as <https://github.com/annosaxfdm/ontology/releases/download/23.08/anno.owl>.
Each release *must* include `anno.owl` as attached binary, leading to the dynamic link to the newest version at <https://github.com/annosaxfdm/ontology/releases/latest/download/anno.owl>.
Each release *must not* be set as pre-release because that breaks the GitHub shorthand link.

## Validation

Install [pySHACL](https://github.com/RDFLib/pySHACL) and execute the `scripts/shacl` shell script.

## See Also

* [Project Website](https://annosaxfdm.de)
* [Paper (under development)](https://github.com/annosaxfdm/anno-paper-swj)
* [Project Website Repository](https://github.com/annosaxfdm/annosaxfdm.de)
* [Anno Ontology Lookup Service (OLS)](https://ols.imise.uni-leipzig.de/index)
* [Anno OLS Repository](https://github.com/annosaxfdm/ols)
* [OLS Synchronization Component Repository](https://github.com/annosaxfdm/olsync)
