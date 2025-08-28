# OpenAI API Reference (Unofficial) — Plain Text & Markdown Mirror

> Two offline-friendly mirrors of the OpenAI **API Reference — Introduction** page for quick search, grepping, and RAG ingestion. This repo is community-maintained and **not affiliated with OpenAI**.

## Files
- `openai_api_reference.txt` — plain-text clone of the API Reference page’s content.
- `openai_api_reference.md` — **normalized Markdown** clone (headings, code fences, and links standardized).

> Scope: captures the sidebar sections under **API Reference → Introduction/Authentication/Debugging/Backward compatibility** and the **Responses API** block visible in the navigation at the time of capture (Aug 2025).

## Provenance & Source
- Canonical docs: <https://platform.openai.com/docs/api-reference/introduction>
- Single-file doc bundle surfaced on X by OpenAI: <https://cdn.openai.com/API/docs/txt/llms-full.txt>.

## Integrity
SHA-256 checksums as of 2025-08-28:

| File | Size | SHA-256 |
|---|---:|---|
| `openai_api_reference.txt` | 4515.72 KiB | `557a862b1574e4d12d645fd9c436fbfd35d487539f104b89dcfa48ad8f0e678b` |
| `openai_api_reference.md` | 4517.35 KiB | `be1e28d92d6995dc80c0f4ba02e8623fb5773b6f686504f86f839fabcda37777` |

## Typical Uses
- **Search/grep:** `rg -n "Responses API" openai_api_reference.*`
- **RAG ingestion:** split by headings, chunk to ~1–2k tokens, index with your vector store of choice.
- **Cursor/IDE context:** drop the `.txt` into your project context window for fast lookup.

## Versioning
This mirror is a point-in-time capture. The canonical docs change; for the latest, always consult the official site above. Consider pinning a tag that matches your project’s doc snapshot.

## Licensing & Attribution
- All documentation content belongs to **OpenAI** and is subject to OpenAI’s website terms. This repository provides an unofficial mirror for **reference and educational** purposes.
- If you redistribute, retain attribution and link back to the canonical docs.

## Safety
- No API keys or secrets are included. Examples use placeholder values.
- Validate any rate limits, headers, and SDK examples against the latest upstream docs before production use.

## Contributing
Issues and PRs that improve formatting, heading structure, or fix copy/paste artifacts are welcome. Please avoid adding generated content that could diverge from the canonical source.

---

**Keywords:** openai api reference, responses api, assistants, embeddings, vector stores, rest api, markdown mirror, plain text, offline docs
