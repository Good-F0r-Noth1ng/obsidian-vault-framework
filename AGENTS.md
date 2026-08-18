# Vault Governance

This repository is a generic Obsidian knowledge-vault framework. Apply local user instructions first. Treat this file as the vault-level policy and the `skills/` directory as workflow guidance.

## Evidence layers

- `raw/` stores original files. After a verified import, do not modify, rename, move, or delete them.
- `derived/` stores rebuildable readable artifacts mapped to `raw/`. Do not create or change it during a Wiki-ingest task.
- `wiki/` stores curated Markdown knowledge. Do not copy a full source artifact into it.

## Change protocol

1. Inspect the vault rules, index, and relevant source before proposing a change.
2. Keep source selection, content planning, and file-writing confirmation separate.
3. Before a controlled write, show the exact files to create or modify and wait for explicit confirmation.
4. Restrict the write to the confirmed list and verify the final scope.
5. Update `wiki/index.md` only when navigation changes. Append to `wiki/log.md` only after a confirmed write actually succeeds.

## Evidence integrity

- Distinguish source facts, personal understanding, inferences, and open questions.
- Preserve source paths or stable source identifiers for consequential claims.
- Do not claim that a model, experiment, or procedure was executed without its recorded conditions and outputs.
- Do not generate OCR, conversions, exports, or simulations without explicit user approval for that operation.

## Directory guidance

- Use `inbox/` for temporary capture and classify it before long-term use.
- Keep `raw/` and `derived/` type folders mirrored when practical.
- Use `wiki/` for knowledge that is useful beyond one source or one session; retain links to the source note rather than duplicate text.
- Treat `archive/` as inactive material. Preserve history unless deletion is explicitly approved.

## Skill routing

Use `obsidian-raw-import` for external source imports, `obsidian-derived-import` for readable artifacts, `obsidian-ingest-to-wiki` for source-grounded notes, and `obsidian-vault-lint` for read-only health audits. Split cross-layer work into separate tasks.
