# Obsidian Vault Framework

A reusable, source-aware Obsidian vault template for long-term learning, research, and project knowledge.

## What this repository provides

- A staged `raw/` -> `derived/` -> `wiki/` knowledge workflow.
- A concise vault governance file (`AGENTS.md`).
- Reusable page templates and a minimal navigation structure.
- Four optional Codex skills for importing, ingesting, and auditing a governed vault.

This is a **framework repository**, not a live personal vault. It deliberately contains no copyrighted sources, private notes, data, credentials, or generated OCR artifacts.

## Quick start

1. Create a new vault from this directory in Obsidian.
2. Read `AGENTS.md` before using an AI agent to modify the vault.
3. Capture unsorted items in `inbox/`, preserve external material in `raw/`, create readable representations in `derived/` only when needed, and curate reusable knowledge in `wiki/`.
4. Adapt the category folders under `wiki/` to your domain without changing the evidence boundaries.

The default `.gitignore` keeps live vault content out of this public framework. In a private derivative vault, revise it deliberately if you want to version personal notes.

## Layout

| Area | Purpose | Default write policy |
| --- | --- | --- |
| `inbox/` | Unclassified capture | Mutable |
| `raw/` | Original source material | Immutable after verified import |
| `derived/` | Rebuildable readable artifacts tied to `raw/` | Controlled, confirmation-gated |
| `wiki/` | Curated, source-aware knowledge | Controlled, confirmation-gated |
| `templates/` | Reusable note templates | Framework-maintained |
| `docs/` | Architecture and publishing guidance | Framework-maintained |
| `skills/` | Optional Codex skills | Framework-maintained |

See [docs/architecture.md](docs/architecture.md) for the workflow and [docs/publishing.md](docs/publishing.md) for the publication boundary.

## Optional skills

The `skills/` directory contains standalone skills. Copy only the skills you need into your Codex skills directory or keep this repository as a project-local reference.

- `obsidian-raw-import`
- `obsidian-derived-import`
- `obsidian-ingest-to-wiki`
- `obsidian-vault-lint`

## License

The framework's original templates, scripts, and skills are released under the [MIT License](LICENSE). Your own sources and notes remain your responsibility and are not licensed by this repository.
