# Project Manager API

Merging a PR will update:

- [API Docs](https://project-manager.docs.buildwithfern.com)

## What is in this repository?

This repository contains

- Project Manager's OpenAPI spec which lives in the [openapi](./fern/openapi/) folder
- The guides written in Markdown

To make sure that the OpenAPI is valid, you can use the Fern CLI.

```bash
npm install -g fern-api
fern check
```

## What are generators?

Generators read in your API Definition and output artifacts (e.g. TypeScript SDK) and are tracked in [generators.yml](./fern/api/generators.yml).

To trigger the generators run:

```bash
fern generate

fern generate --group publish --version <version>
```
