\# County-HexHunt



> **Status: Work in Progress**  

> This repository is a **preview / announcement** only. **No script files are published here yet.**  

> Active development is ongoing. Source and assets will be released through an official **paid** storefront when the product is ready.



**Supernatural-style creature hunts** for FiveM (QBCore + ox\_lib + ox\_inventory).  

Designed for immersive RP servers — hunt contracts, rituals, silver rounds, and a Hunter Market.



\---



\## What is this?



`County-HexHunt` turns night-time into a hunter’s shift. Players pick up contracts from a **Hunt Board**, gear up at the **Hunter Market**, track targets with an **EMF Reader** and finish creatures with **rituals + silver** — inspired by classic monster-hunter TV lore (ghosts, vampires, demons, beasts, and more).



Built for **County-Style** worlds, but configurable for other maps via spawn zones.



\---



\## Planned / current features



\### Core loop

\- Hunt Board contracts with categories (ghosts, vampires, demons, beasts, monsters…)

\- Night-window gating (configurable)

\- Search zone (map radius) → creature spawn on entry

\- Contract rewards: Cash + \*\*Essence\*\*

\- Field Notes / case files unlocked after successful kills

\- Leaderboard (IC name, hunt count, ranks)



\### Creatures \& combat

\- Multiple creature types with unique weaknesses, HP, FX, and attack styles

\- Aggressive AI / power attacks (magic \& melee)

\- Ritual requirements (salt circle, holy water, exorcism, Devil’s Trap, and more)

\- Silver (and related) ammunition rules

\- Defeat handling without hard character death (wake near the zone)



\### Hunter Market \& gear

\- Vendor NPC + modern NUI shop (weapons, ammo, rituals, equipment)

\- Temporary hunt weapons locked outside an active contract

\- Anti-PvP with hunt weapons (cannot freely use them on other players)

\- Vehicle \*\*Hunt Armory\*\* kit (install / remove via target, stash persists with the kit)



\### UX

\- Modern Hunt Board \& Market UI with page transitions

\- In-hunt HUD (HP, silver, EMF, ritual hints / “Bobby tips”)

\- Floating 3D prompt at the Hunt Board



> Feature set is still evolving while the script is under active development.



\---



\## Requirements (target stack)



| Resource        | Role                          |

|-----------------|-------------------------------|

| **QBCore**      | Framework                     |

| **ox\_lib**      | UI / progress / callbacks     |

| **ox\_inventory**| Items, weapons, stashes       |

| **qb-target** or **ox\_target** | Interactions (board / armory) |



Optional: custom ped packs for creature models (configurable fallbacks included).



\---



\## Installation



**Not available as a public download from this repository.**



When released commercially:

1\. Purchase from the official listing (Tebex / CFX Assets — link TBA)

2\. Download via Keymaster / escrow as instructed

3\. Drop into `resources`, add `ensure County-HexHunt` (and any ped pack deps)

4\. Add items to `ox\_inventory` as documented in the paid package

5\. Configure `config.lua` (board/vendor coords, creatures, shop, night hours)



Until then: this GitHub page is informational only.



\---



\## Configuration



A single shared `config.lua` will drive:

\- Board \& vendor locations

\- Creature roster (models, HP, rewards, weaknesses, spawn zones)

\- Shop catalog

\- Ritual / ammo / armory settings

\- Night hours \& hunt area radius



Exact config reference ships with the paid release.



\---



\## License (commercial)



This project is \*\*proprietary paid software\*\*.



\- **Not** open source  

\- **Not** free to redistribute  

\- Purchase grants a license to run on \*\*one\*\* FiveM server you operate  

\- Resale, leaks, public re-uploads, and escrow bypass are \*\*forbidden\*\*



See \[`LICENSE`](./LICENSE) for the full \*\*Proprietary Software License\*\*.



Unauthorized distribution may result in license termination and storefront / Keymaster action.



\---



\## Roadmap (high level)



\- \[x] Core hunt loop \& rituals  

\- \[x] Hunter Market + NUI polish  

\- \[x] Vehicle armory \& weapon locks  

\- \[x] Field notes / leaderboard  

\- \[ ] Final balance pass \& docs for release  

\- \[ ] Public paid listing (Tebex / CFX)  

\- \[ ] Post-release updates \& support channel  



\*(Checklist will update as development continues.)\*



\---



\## Support \& purchase



\- **Purchase:** Coming soon (official storefront link will be added here)  

\- **Support:** Via the storefront ticket / Discord linked on the product page (TBA)  

\- **Issues on this repo:** Please use discussions / issues only for **public questions about the product**. Do not request free copies of the script.



\---



\## Credits



Developed for FiveM RP Creature-Hunters everywhere.



**by pacxwheaa**



