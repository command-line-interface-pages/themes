# Contributing guide

## Prerequisites

### Visual Studio Code

- [common extensions](https://command-line-interface-pages.github.io/site.github.io/extensions/)
- YAML:
  - [YAML (linter, formatter, intellisence, snippets)](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

## How to get started?

Before writing your own theme try to explore existing ones with preinstalled prerequisites.
Start with the simplest [default](./default/theme.yaml) theme.

Each theme can set up one or several following aspects of rendered pages:

- header
- summary
- examples

To make setup agile it's allowed to surround header, summary and examples with any
text. `prefix` and `suffix` properties are responsible for that. They can be omitted
in which can nothing is put around header/summary/examples.

To change color of header/summary/examples itself use `color` property.
