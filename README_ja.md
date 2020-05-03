<!-- @head-content@ -->
# laplacian/project.project-types

The basic project types used in the Laplacian project.


*Read this in other languages*: [[English](README.md)] [[简体中文](README_zh.md)]
<!-- @head-content@ -->

<!-- @toc@ -->
## Table of contents
1. [使用方法](#使用方法)
1. [インデックス](#インデックス)


<!-- @toc@ -->

<!-- @main-content@ -->
## 使用方法

この modelモジュールを適用するには、プロジェクト定義に以下のエントリを追加してください。
```yaml
project:
  models:
  - group: laplacian
    name: project.project-types
    version: 1.0.0
```

下記のコマンドを実行すると、このモジュールの適用によって影響を受ける資源の一覧とその内容を確認できます。

```console
$ ./script/generate --dry-run

diff --color -r PROJECT_HOME/.NEXT/somewhere/something.md PROJECT_HOME/somewhere/something.md
1,26c1,10
< content: OLD CONTENT
---
> content: NEW CONTENT
```

内容に問題が無ければ、下記コマンドを実行して変更を反映してください。

```console
$ ./script/generate --dry-run

```


## インデックス


### ソースコード一覧


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