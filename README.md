<!-- @head-content@ -->
# laplacian/project.project-types

The basic project types used in the Laplacian project.


*Read this in other languages*: [[日本語](README_ja.md)] [[简体中文](README_zh.md)]
<!-- @head-content@ -->

<!-- @toc@ -->
## Table of contents
1. [Usage](#Usage)
1. [Index](#Index)


<!-- @toc@ -->

<!-- @main-content@ -->
## Usage

To apply this model module, add the following entry to your project definition.
```yaml
project:
  models:
  - group: laplacian
    name: project.project-types
    version: 1.0.0
```

You can run the following command to see a list of resources affected by the application of this module and their contents.
```console
$ ./script/generate --dry-run

diff --color -r PROJECT_HOME/.NEXT/somewhere/something.md PROJECT_HOME/somewhere/something.md
1,26c1,10
< content: OLD CONTENT
---
> content: NEW CONTENT
```

If there is no problem, execute the following command to reflect the change.
```console
$ ./script/generate --dry-run

```


## Index


### Source code list


- [model/project/sources.yaml](<./model/project/sources.yaml>)
- [model/project.yaml](<./model/project.yaml>)
- [src/project_types/arch-model.yaml](<./src/project_types/arch-model.yaml>)
- [src/project_types/domain-model.yaml](<./src/project_types/domain-model.yaml>)
- [src/project_types/generator.yaml](<./src/project_types/generator.yaml>)
- [src/project_types/model.yaml](<./src/project_types/model.yaml>)
- [src/project_types/plugin.yaml](<./src/project_types/plugin.yaml>)
- [src/project_types/schema-model.yaml](<./src/project_types/schema-model.yaml>)
- [src/project_types/schema-plugin.yaml](<./src/project_types/schema-plugin.yaml>)
- [src/project_types/service-generator.yaml](<./src/project_types/service-generator.yaml>)
- [src/project_types/template.yaml](<./src/project_types/template.yaml>)


<!-- @main-content@ -->