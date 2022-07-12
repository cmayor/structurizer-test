# Welcome

This repo serves as an example of lightweight local-only or static pages [Structurizr](https://structurizr.com/) hosting using MkDocs to serve generated diagrams as well as additional documentation.

## Structurizr Diagrams

These diagrams have been exported to a Mermaid file from the [Structurizr workspace/model](https://github.com/cmayor/structurizer-test/blob/main/workspace.dsl) and included using mkdocs macros plugin.

### System Context Diagram

```mermaid
{% include 'diagrams/structurizr-Diagram1.mmd' %}
```

## Container Diagram

```mermaid
{% include 'diagrams/structurizr-Diagram2.mmd' %}
```

## PlantUML

This is a PlantUML diagram generated using the [C4 extensions](https://github.com/plantuml-stdlib/C4-PlantUML)

[PlantUML source](https://github.com/cmayor/structurizer-test/blob/main/docs/diagrams/src/basic.puml)

![file](diagrams/out/C4_Elements.svg)
