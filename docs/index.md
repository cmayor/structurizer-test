# Welcome

This repo serves as an example of lightweight local-only or static pages Structurizr hosting using MkDocs to serve generated diagrams as well as additional documentation.

## System Context

This diagram has been exported to a Mermaid file from the Structurizr workspace/model, and included using mkdocs macros plugin.

```mermaid
{% include 'diagrams/structurizr-Diagram1.mmd' %}
```

## Container

This is another diagram.

```mermaid
{% include 'diagrams/structurizr-Diagram2.mmd' %}
```

## PlantUML

![file](diagrams/out/basic.png)
