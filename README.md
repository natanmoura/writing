# Writing

Rough thinking space. Nothing here is finished writing.

## How it works

1. **Dump** — Natan talks or types freely about an idea. Claude saves it word-for-word in `raw/`.
2. **Organize** — Claude pulls the thoughts into `topics/`, one file per topic, grouped and tidied, with links back to the raw dumps they came from. New dumps on an existing topic get merged into that topic's file.
3. **Surface** — When a topic has enough substance, Claude proposes possible articles in `ideas/`: angle, core argument, rough outline, open questions.
4. **Write** — Natan writes the final piece in their own words, elsewhere or in a later pass.

## Folders

| Folder | What goes in it | Who edits |
|---|---|---|
| `raw/` | Verbatim dumps, never edited after saving. Named `YYYY-MM-DD-short-slug.md`. | Saved as-is |
| `topics/` | Organized notes per topic: key claims, examples, tensions, open questions, sources. | Claude, revised over time |
| `ideas/` | Candidate articles built from one or more topics. | Claude proposes, Natan decides |

## Rules

- Raw dumps are the source of truth. Organizing never deletes or rewrites them.
- Topic notes keep Natan's phrasing where it's distinctive; Claude marks its own additions or inferences.
- Contradictions between dumps are kept and flagged, not smoothed over.
