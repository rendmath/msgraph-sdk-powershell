
### AutoRest Configuration

> see https://aka.ms/autorest

``` yaml
require:
  - $(this-folder)/../../../readme.graph.md
title: $(service-name)
subject-prefix: ''
input-file: $(spec-doc-repo)/$(title).yml
```

### Versioning

``` yaml
module-version: 0.1.1
release-notes: 'Initial release.'
```
