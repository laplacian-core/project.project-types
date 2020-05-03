<!-- @head-content@ -->
# laplacian/project.project-types

The basic project types used in the Laplacian project.


*Read this in other languages*: [[English](README.md)] [[日本語](README_ja.md)]
<!-- @head-content@ -->

<!-- @toc@ -->
## Table of contents
1. [如何使用](#如何使用)
1. [索引](#索引)


<!-- @toc@ -->

<!-- @main-content@ -->
## 如何使用

要应用此model模块，请在项目定义中加入以下条目

```yaml
project:
  models:
  - group: laplacian
    name: project.project-types
    version: 1.0.0
```

您可以运行以下命令查看受本模块应用影响的资源列表及其内容

```console
$ ./script/generate --dry-run

diff --color -r PROJECT_HOME/.NEXT/somewhere/something.md PROJECT_HOME/somewhere/something.md
1,26c1,10
< content: OLD CONTENT
---
> content: NEW CONTENT
```

如果没有问题，请执行下面的命令来反映变化

```console
$ ./script/generate --dry-run

```


## 索引


### 源码列表


- [model/project/document/document.yaml](<./model/project/document/document.yaml>)
- [model/project/document/sections/index.yaml](<./model/project/document/sections/index.yaml>)
- [model/project/document/sections/usage.yaml](<./model/project/document/sections/usage.yaml>)
- [model/project/document/sections.yaml](<./model/project/document/sections.yaml>)
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