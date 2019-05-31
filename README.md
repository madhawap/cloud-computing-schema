# Cloud IaaS Schema
The development version of the ontology is in [ontology_dev](ontology_dev/README.md).

We have also registerd an entry at http://prefix.cc for `cocoon`.

# Data
1. [Most updated data in seperated files](example/sparql-generate/result/)
2. [Single data dump of all v1.0.1 files](data/v1_0_1.ttl)

# Permalink with w3id
https://w3id.org/cocoon/v1.0.1

Prefered to be used as:

    @prefix cocoon: <https://w3id.org/cocoon/v1.0.1#>

Linked Data Fragments Server: https://w3id.org/cocoon/data

Old Version https://w3id.org/cocoon/v0.1

[Notes on deployment to w3id.](w3id.md)

# Sites
The documentation site is hosted via Github page.
Source code is in the [gh-page branch](https://github.com/miranda-zhang/cloud-computing-schema/tree/gh-pages).
See [widoco](widoco/README.md) about documentation generation.

Linked Data Fragments Server hosted on Google Cloud:
http://35.231.131.100:5000
(Permalink:https://w3id.org/cocoon/data)

Source code is in the [ldf-server branch](https://github.com/miranda-zhang/cloud-computing-schema/tree/ldf-server).

# Docuemtation
1. [Quick Start](example/quickstart.md) listed some short examples for the simplest use cases.
2. [Vocabularies](vocabularies.md).
3. For advanced modelling, see the [complete examples](example/README.md), which shows various ways to access and use this ontology.
4. [Latest Changes](revision_history.md).

# Publications
[BibTeX](BibTeX.md)

# Dependencies
This project used solutions from the following projects:
1. https://github.com/perma-id/w3id.org/
2. https://github.com/stedolan/jq
   - https://stedolan.github.io/jq/manual/
3. https://github.com/sparql-generate/sparql-generate
   - https://ci.mines-stetienne.fr/sparql-generate/apidocs/allclasses-noframe.html
4. https://github.com/dgarijo/Widoco
5. https://github.com/LinkedDataFragments/Server.js/
6. https://github.com/schemaorg/schemaorg
   - https://schema.org/docs/developers.html
