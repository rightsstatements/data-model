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

The current rights statements are located in [`rights-statements.ttl`](rights-statements.ttl) and language specific JSON-LD files.

Implementing translations
---

[Transifex](https://www.transifex.com/graphthinking-gmbh/rightsstatementsorg/) is used to carry out translations of the statements and collections. They are tagged with the category `data-model`. Please get in touch with the [maintainers](https://www.transifex.com/graphthinking-gmbh/rightsstatementsorg/settings/maintainers/) to add a new language to the project.

To incorporate updates or new translations, install [`tx`](https://docs.transifex.com/client/introduction), run [`tx pull`](https://docs.transifex.com/client/pull#command-options) and commit the changes into your local clone (the tx client needs an API token available in your Transifex account settings). This needs to be done for all repositories where there are translations (data-model, etc). The language of the translation being pulled can be specified in a parameter (otherwise the selection can be done in the commit from local to reference).

For deployment you have to re-start the service with rights-deploy. See also notes on implementing translations for the [rights app](https://github.com/rightsstatements/rights-app/blob/master/README.md) and the [website](https://github.com/rightsstatements/rightsstatements.github.io/blob/master/README.md) for more information.

License
---

* [CC0](https://creativecommons.org/publicdomain/zero/1.0/)
