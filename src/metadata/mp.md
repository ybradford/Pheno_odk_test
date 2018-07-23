---
layout: ontology_detail
id: mp
title: Pheno_odk_test
jobs:
  - id: https://travis-ci.org/obophenotype/pheno-odk-test
    type: travis-ci
build:
  checkout: git clone https://github.com/obophenotype/pheno-odk-test.git
  system: git
  path: "."
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: Pheno_odk_test is an ontology...
domain: stuff
homepage: https://github.com/obophenotype/pheno-odk-test
products:
  - id: mp.owl
  - id: mp.obo
dependencies:
 - id: po
 - id: ro
 - id: pato
tracker: https://github.com/obophenotype/pheno-odk-test/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here
