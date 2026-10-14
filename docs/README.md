# KismoTech docs

Cross-repository decisions and the repository map for the Kismo platform and products.

| Doc | What it covers |
|---|---|
| [repositories.md](repositories.md) | Every repository: role, visibility, licence, dependencies |
| [decisions/0001-platform-layering.md](decisions/0001-platform-layering.md) | Platform layering, open/closed split, licences, BSP boundary |

**Upstream:** the Kismo platform builds on the [Sub0 libraries](https://github.com/CraigHutchinson/.github/tree/main/docs).
Dependencies point one way: Kismo uses Sub0, never the reverse.

Each repository absorbs what applies to it through its own README and decision records, and links back here.
Product-internal detail stays in the (private) product repositories.
