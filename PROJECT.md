# DnDWiki — Vecna

This public repository is the generated player-facing publication target for the Vecna campaign.

## Authority

- Canonical campaign writing remains in the DM's private Obsidian vault.
- Reusable engine/plugin/parser/UI source belongs to `thatoneguydan/dndwiki`.
- This repository owns only Vecna publication configuration, generated player-safe/perspective-tagged content/assets/runtime output, and its eventual GitHub Pages deployment configuration.
- This repository is never a full-vault mirror and is never a second authoring copy.

## Privacy boundary

DM-only ordinary note content and the player-registry source note must never enter this repository. Player-keyed sections are intentionally publishable under DnDWiki's lightweight personalization threat model. Generated state must identify the DnDWiki schema/engine version that produced it.

## Read next

- `dndwiki.campaign.json` — campaign publication/deployment contract.
- `thatoneguydan/dndwiki/ARCHITECTURE.md` — engine-wide publication/privacy semantics.
- `thatoneguydan/dndwiki/ROADMAP.md` — canonical program roadmap.

## Current position

Vecna deployment work remains **pre-service** and follows the reusable-campaign gate after De Drakengardt proves the engine boundary. No live vault connection, campaign corpus publication, Pages deployment, or custom-domain operation is authorized by this bootstrap.

## Safety constraints

- Never commit private DM-only source or the player registry.
- Never infer publishability from folder location alone; generated output must come from the DnDWiki extraction contract.
- Do not require Gigachomper, grimoireOS, the DM's home power, or residential internet to serve already-published content.
