# Repositories

| Repository | Role | Visibility | Licence | Depends on |
|---|---|---|---|---|
| [KismoCore](https://github.com/KismoTech/KismoCore) | Data contracts: records, journal, time base, replay, decoders | Public | MIT | Sub0 |
| [KismoEngine](https://github.com/KismoTech/KismoEngine) | App / simulation / game runtime | Public | AGPL-3.0-only or commercial | KismoCore, Sub0 |
| KismoEdge | Firmware runtime on Zephyr; defines the BSP contract | Private | Proprietary | KismoCore, Sub0 |
| KismoBspNrf54 | Board support for Nordic nRF54 | Private | Proprietary | KismoEdge's contract |
| BikeDynamics | Bicycle dynamics models for PhantomFlow: C++23 ports of the BikeLab stations, on Sub0Physics | Private | Proprietary | Sub0Physics |
| PhantomFlow | Product: design and system repository | Private | Proprietary | Kismo platform |
| [PhantomFlow.uk](https://github.com/KismoTech/PhantomFlow.uk) | Product website ([live](https://kismotech.github.io/PhantomFlow.uk/)) | Public | — | — |
| Pouncer | Product: collar firmware and tools | Private | Proprietary | Sub0; Kismo platform (planned) |
| [Pouncer.uk](https://github.com/KismoTech/Pouncer.uk) | Product website ([pouncer.uk](https://pouncer.uk)) | Public | — | — |
| [.github](https://github.com/KismoTech/.github) | Organisation profile and these docs | Public | — | — |

Outside the organisation:

- the [Sub0 libraries](https://github.com/CraigHutchinson/.github/blob/main/docs/sub0-family.md) (upstream);
- [Crucible](https://github.com/CraigHutchinson/Crucible), a public game that is planned to consume KismoEngine as its proving consumer.

All copyright is held by Craig Hutchinson. KismoTech is a GitHub organisation that groups the repositories.
