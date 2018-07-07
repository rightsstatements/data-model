rightsstatements.org data model
===

[![Build Status](https://travis-ci.org/rightsstatements/data-model.svg)](https://travis-ci.org/rightsstatements/data-model)

This repository contains the implementation of interoperable rights
statements developed for [RightsStatements.org](http://rightsstatements.org/). 
More information about the motivation and implementation of these statements
can be found in the following white papers:

* [Recommendations for Standardized International Rights Statements](http://rightsstatements.org/en/documentation/rights-statements-white-paper/)
* [Requirements for the Technical Infrastructure for Standardized International Rights Statements](http://rightsstatements.org/en/documentation/technical-white-paper/)

The rights statements are currently implemented as a [SKOS](http://www.w3.org/2004/02/skos/)
vocabulary serialized in [Turtle](http://www.w3.org/TR/turtle/).

If you have feedback, you can either [open an issue on GitHub](https://github.com/rightsstatements/data-model/issues)
or contact one of the technical co-chairs:

* Mark A. Matienzo <matienzo@stanford.edu>
* Antoine Isaac <aisaac@few.vu.nl>

Contents
--- 

* The current rights statements are located in [`rights-statements.ttl`](rights-statements.ttl). Note that the RDF assertions within this file are organized to make translations easier. Committers should ensure they do not jeopardize this organization!
* An example file, which contains rights statements with a different version and containing sample, unofficial translations, can be found in [`example-versions.ttl`](example-versions.ttl).

License
---

* [CC0](https://creativecommons.org/publicdomain/zero/1.0/)
