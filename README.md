# Neo4j GitHub Action

Github action to setup a neo4j database.

Inspired by [https://github.com/nijel/rabbitmq-action](https://github.com/nijel/rabbitmq-action)

## Usage

```yml
steps:
  - uses: KarakoA/setup-neo4j@v1.1.1
```

Default user and passwort are `neo4j` and `ci`. Password and version can be set via

```yml
steps:
  - uses: KarakoA/setup-neo4j@v1.1.1
    with:
      tag: '4.2.1'
      passwort: NEO4J
```

