# ALIGN Pharmaceuticals Pipeline

This repository is the public home of the ALIGN Pharmaceuticals Pipeline documentation. It explains how ALIGN resolves health-product identity and integrates policy, regulatory, qualification, clinical, innovation, and FDA evidence into a provenance-preserving analytical model.

## Documentation website

The Quarto website is published through GitHub Pages at:

<https://align-globalhub.github.io/PharmaceuticalsPipeline/>

The site is generated from the source documents in [`docs/`](docs/).

## Current scope

The repository currently contains public documentation and approved aggregate figures. It intentionally does not contain raw, licensed, row-level, or operational pipeline data.

Reusable pipeline code, schemas, tests, and synthetic examples will be migrated here incrementally after they have been separated from development data and workstation-specific configuration.

## Render locally

Install [Quarto](https://quarto.org/docs/get-started/) and run:

```bash
quarto preview docs
```

To create a production build:

```bash
quarto render docs
```

The rendered site is written to `docs/_site/` and is not committed. Documentation execution is disabled in the public project so the site can render without private pipeline data.

## Repository boundary

Development data, generated database exports, caches, and exploratory analysis remain outside this public repository. Pull requests are checked for prohibited data files before documentation is rendered or deployed.

## License

The software and documentation in this repository are available under the [MIT License](LICENSE).

