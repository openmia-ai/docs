# OpenMIA Docs

This repository contains the public documentation site for OpenMIA.

The site is built with Mintlify. The main configuration lives in `docs.json`, and pages are written as MDX files.

## Local preview

Install the Mintlify CLI if it is not already available:

```bash
npm i -g mint
```

Run the preview server from the repository root:

```bash
mint dev
```

Mintlify serves the docs preview locally, usually at `http://localhost:3000`.

## Current documentation areas

- OpenMIA overview and quickstart
- OpenMIA App Observation user guide

## Writing guidelines

- Write in English.
- Use active voice and second person.
- Prefer task-oriented pages over internal implementation notes.
- Use placeholder secrets such as `omia_ing_xxx`.
- Do not commit real tokens, cookies, API keys, OAuth secrets, or provider credentials.

## Publishing

Changes are deployed by the Mintlify/GitHub integration after they are merged into the configured production branch.
