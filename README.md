# \# THE WEFT — D\&D Campaign Vault

# 

# > \*The great Weft has existed in obliviousness to the gods and mortals that roamed inside its vastness, until now.\*

# 

# An \[Obsidian](https://obsidian.md/) campaign vault for \*\*THE WEFT\*\*, a multiverse D\&D setting. Built on Josh Plunkett's \[Obsidian TTRPG Tutorials](https://obsidianttrpgtutorials.com/) vault template, so every worldbuilding note is a structured, wikilinked, Dataview- and graph-ready entry rather than a loose document.

# 

# \---

# 

# \## The setting

# 

# THE WEFT (called \*\*The Hang\*\* by those who live in it) is a woven multiverse: countless parallel worlds strung side by side like cloth on a loom, held in tension by \*\*six cosmic forces\*\* — the Evocade, Tethyne, Sijill, Tehom, Nifling, and Raijin.

# 

# Worlds are threads. To be \*cut\* is to fall into the \*\*Underdrop\*\*; to be \*kept\* is to be filed in \*\*the Anthology\*\* — recorded, then quietly allowed to die. The campaign's central horror lives in the gap between those two fates.

# 

# The player characters are \*\*Editions\*\*: living copies smuggled out of the Anthology, archived duplicates of originals whose worlds were "saved." Each carries a \*fidelity\* rating that drifts over time. At the center of it all sits the betrayer-god \*\*al-Kutbā\*\*, who wears his archived twin \*\*Dushara\*\* as a mask.

# 

# The primary investigation arc is the \*\*Peripeteia\*\*, a two-session (\~6–8 hour) module in which the party forces that mask off.

# 

# \---

# 

# \## Repository structure

# 

# This repo is the source of truth for the vault. The Obsidian vault itself lives under `ObsidianTTRPGVault/`:

# 

# | Folder | Contents |

# |---|---|

# | `2-World/` | \*\*All worldbuilding content\*\* — the canonical setting notes (locations, people, groups, quests, species). |

# | `1-DM Toolkit/` | GM-facing material, including the `THE WEFT/` source docs (`THE\_WEFT\_Peripeteia.docx` + companion knowledge tree). |

# | `1-Party/`, `1-Session Journals/` | Party roster and play-session logs. |

# | `3-Mechanics/` | Imported rules compendium (\~15k files). \*\*Not worldbuilding\*\* — excluded from any world audit. |

# | `z\_Templates/`, `z\_Assets/` | Note templates and image/asset store. |

# | `0-Obsidian TTRPG Tutorial/` | The original template's tutorial notes. |

# 

# > ⚠️ The subfolder names under `2-World/` (`Galaxies`, `Hubs`, `Quests`, etc.) are \*\*hard-coded into the note templates\*\*. Renaming them silently breaks Templater/meta-bind generation. See `2-World/Important - Read Me.md`.

# 

# \---

# 

# \## Current world state

# 

# The `2-World` folder currently holds \*\*25 authored WEFT notes\*\* alongside the template's original "Test" placeholders. All authored notes have valid parent links — \*\*no broken containment links and no orphans\*\*.

# 

# \### Containment tree

# 

# ```

# The Weft (Galaxy / "The Hang")

# ├── The Anthology              (Point of Interest)

# ├── The Underdrop              (Point of Interest)

# ├── The Editions               (Sapient Species — what the party are)

# ├── Cosmic forces (Groups): Evocade · Tethyne · Sijill · Tehom · Nifling · Raijin

# ├── The Errata                 (Group — the smugglers)

# ├── The Exodos                 (Quest)

# ├── The Unravelling Thread     (Region — the party's lost origin world)

# │   └── The Prologos           (Quest)

# └── The Slack-Tide             (Hub)

# &#x20;   ├── The Tally-Car          (Place)

# &#x20;   ├── The Vintner's Car      (Place)

# &#x20;   │   ├── al-Kutbā           (People — the betrayer-god)

# &#x20;   │   └── Dushara            (People — the archived twin / mask)

# &#x20;   ├── Oresh                  (People)

# &#x20;   ├── al-ʿUzzā               (People)

# &#x20;   ├── The Parodos            (Quest)

# &#x20;   ├── The Peripeteia         (Quest — the structural hinge)

# &#x20;   └── The Anagnorisis        (Quest)

# ```

# 

# \### The Quest arc

# 

# A five-movement tragic structure, named for the parts of a Greek drama:

# 

# 1\. \*\*The Prologos\*\* — the setup, in the lost origin world.

# 2\. \*\*The Parodos\*\* — arrival and the false rescue.

# 3\. \*\*The Peripeteia\*\* — the reversal; the two-session investigation module and central hinge.

# 4\. \*\*The Anagnorisis\*\* — the recognition.

# 5\. \*\*The Exodos\*\* — the departure.

# 

# \### The six cosmic forces

# 

# Modeled as `Group` notes with live `allies`/`enemies` standing blocks. Current alignments: the \*\*Tehom\*\* stands opposed to every other force; \*\*Evocade–Raijin–Tethyne\*\* and \*\*Sijill–Nifling\*\* form the two main blocs, with the Sijill and Tethyne locked as enemies.

# 

# \---

# 

# \## The knowledge-tree tool

# 

# The vault is audited with the \*\*`dnd-worldtree`\*\* skill (`build\_knowledge\_tree.py`), a read-only parser that reads \*only\* the YAML frontmatter of `2-World` notes — never the note bodies, which contain Templater/meta-bind code.

# 

# ```bash

# python3 build\_knowledge\_tree.py \\

# &#x20; --vault ObsidianTTRPGVault \\

# &#x20; --subdir 2-World \\

# &#x20; --out ./out

# ```

# 

# Requires `PyYAML`. It outputs:

# 

# \- `knowledge\_tree.md` — the containment tree, a category index, broken-link/orphan sections, and the relationship-edge list.

# \- `knowledge\_graph.json` — nodes + containment edges + relationship edges + stats, for graph view or further analysis.

# 

# Point it at `2-World` only — never at `3-Mechanics/`.

# 

# \---

# 

# \## Authoring conventions

# 

# The vault's data model is what makes the graph, Dataview, and the worldtree tool all work. Each authored note follows these rules:

# 

# \- \*\*Category tag + container.\*\* Every note carries exactly one `Category/<Type>` tag and a `MyContainer:` wikilink to its parent location. These two fields drive placement in the tree and graph.

# \- \*\*Wikilink format.\*\* Cross-references use the full path form: `\[\[2-World/<Folder>/<Name>.md|<Name>]]`.

# \- \*\*YAML quoting.\*\* Any frontmatter value containing a colon \*\*must\*\* be double-quoted (e.g. `questGiver: "\[\[2-World/People/al-Kutbā.md|al-Kutbā]]"`), or the frontmatter fails silently.

# \- \*\*Frontmatter over body.\*\* Keep frontmatter fully correct; don't hand-author the Templater/meta-bind UI machinery in note bodies — the create-note buttons generate that.

# \- \*\*Canon vs. proposal.\*\* Notes still awaiting ratification are flagged with a `> \[!note] Proposed extension` callout so they stay visually distinct from established canon.

# \- \*\*Extra relationship fields\*\* (e.g. `allies`/`enemies` on Groups) are harmless — the graph and the worldtree tool pick them up automatically.

# 

# \---

# 

# \## Roadmap

# 

# \- Flesh out the two thinly-sketched cosmic forces (the \*\*Evocade\*\* and the \*\*Nifling\*\*) to complete the cosmology layer.

# \- Decide whether to fill intermediate location tiers (Star System → Planet → Continent) between the Galaxy root and the Hub level.

# \- Author notes for the \*\*Catastrophe\*\* boss and the \*\*Errata civil-war\*\* content flagged in the campaign bible.

# \- Run a cleanup pass to remove the remaining `Test` placeholder notes from `2-World`.

# 

# \---

# 

# \## Credits

# 

# Setting and content: THE WEFT (this repository).

# Vault framework: the Obsidian TTRPG Vault template by Josh Plunkett 

