---
title: schema
categories: |
  database
version: 0.87.0
database: |
  Show the schema of a SQLite database.
usage: |
  Show the schema of a SQLite database.
---
<!-- This file is automatically generated. Please edit the command in https://github.com/nushell/nushell instead. -->

# <code>{{ $frontmatter.title }}</code> for database

<div class='command-title'>{{ $frontmatter.database }}</div>

## Signature

```> schema {flags} ```


## Input/output types:

| input | output |
| ----- | ------ |
| any   | any    |

## Examples

Show the schema of a SQLite database
```nu
> open foo.db | schema

```
