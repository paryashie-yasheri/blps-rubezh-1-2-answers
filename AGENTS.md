# Rules for this repo

## Images

- All images must be placed in the `images/` folder at repo root, never in repo root directly
- If a new image file appears in the repo root (e.g. `Pasted image *.png`), it must be moved to `images/`
- Image references in markdown files must use standard Markdown syntax: `![alt](images/filename.png)`, not Obsidian `![[filename]]` syntax
- If an Obsidian-style `![[filename]]` reference is found in any markdown file, replace it with the correct `![alt](images/filename.png)` syntax
- Image filenames with spaces: use `%20` URL encoding in markdown paths (e.g. `images/Pasted%20image%2020260613181945.png`)

## Mermaid diagrams

- Mermaid code blocks in markdown must use standard fenced code: ` ```mermaid `
- Russian/non-ASCII text in mermaid node labels must be wrapped in double quotes: `A["Текст на русском"]`
