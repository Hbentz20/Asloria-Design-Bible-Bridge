# Asloria — Bible to GitHub sync

Each run starts fresh. Follow these steps exactly. Never edit the Design Bible. Never summarize, rewrite or reconcile any content.

**Source:** the Claude Docs doc at https://claude.ai/artifact/Dc8Nypw42Rc1r671wapdtd (12 tabs). **Destination:** this repo's `main` branch. Change only `tabs/` and `manifest.json`.

1. **Check for changes.** List the doc's tabs in display order. For each tab, do a minimal read (a search for text that won't match) to get its current revision. Compare each tab's ID and revision with `manifest.json`. If the manifest is missing, treat every tab as changed. If nothing changed, report "No change" and stop without committing.

2. **Export each changed tab** as Markdown with maxBytes 11534336.
   - If the result was saved to a tool-results file, decode it with a Python script that reads that file.
   - If it came back inline, write the encoded text to a file and decode it, then export the tab again and repeat. The two decoded files must have the same sha256 and match the size the connector reported. If they differ, export a third time and keep the version two exports agree on. If no two agree, stop and report without committing. All agreeing exports must report the same revision; record that revision. Mark the tab `"transcribed": true` in the manifest.
   - Never type or edit the content itself.

3. **Write the files.** Save each tab as `tabs/NN-slug.md`, where NN is its display order (01–12) and the slug is its name in lowercase with each run of non-alphanumeric characters turned into one hyphen. Track tabs by ID: if one was renamed or moved, rename its file with `git mv`.

4. **Update `manifest.json`.** Record `doc_url` and `synced_at`, plus one entry per tab: `order`, `name`, `id`, `rev` (the export's own revision), `file`, `bytes`, `sha256` and `transcribed`.

5. **Commit and push.** Commit only once every changed tab is exported and verified. Use the message `Bible sync: <Tab> rev A→B, …` and push to `main`.

6. **Report** the commit ID and each changed tab with its old and new revision. If any step fails, report what failed and stop without committing or pushing.
