rightsstatements.org data model
===

[![Build Status](https://travis-ci.org/rightsstatements/data-model.svg)](https://travis-ci.org/rightsstatements/data-model)

**NOTE: These rights statements are currently in pre-release. Version 1.0 of
the statements will same, but we have yet to roll out our production 
infrastructure to support them. As such, they are not yet dereferenceable.**

This repository contains the proposed implementation of interoperable rights
statements developed by the [International Rights Statement Working Group](http://rightsstatements.org/). 
More information about the motivation and implementation of these statements
can be found in the following white papers:

* [Recommendations for Standardized International Rights Statements](http://rightsstatements.org/files/160208recommendations_for_standardized_international_rights_statements_v1.1.pdf)
* [Requirements for the Technical Infrastructure for Standardized International Rights Statements](http://rightsstatements.org/files/151002requirements_for_the_technical_infrastructure_for_standardized_international_rights_statements.pdf)

The rights statements are currently implemented as a [SKOS](http://www.w3.org/2004/02/skos/)
vocabulary serialized in [Turtle](http://www.w3.org/TR/turtle/).

If you have feedback, you can either [open an issue on GitHub](https://github.com/rightsstatements/data-model/issues)
or contact Mark A. Matienzo, co-chair of the Technical Working Group of the International Rights Statements Working Group, via email at <mark@dp.la>.

Contents
--- 

* The current rights statements are located in [`rights-statements.ttl`](rights-statements.ttl).
* An example file, which contains rights statements with a different version and containing sample, unofficial translations, can be found in [`example-versions.ttl`](example-versions.ttl).

License
---

* [CC0](https://creativecommons.org/choose/zero/)