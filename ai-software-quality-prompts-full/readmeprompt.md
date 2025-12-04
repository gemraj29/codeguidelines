# readmeprompt.md – How to Use This Prompt Pack

1. Use `01-universal-core-prompt-full.md` or `02-universal-core-prompt-micro.md` as your base rules for any LLM.
2. For new projects, start from `03-start-new-project-megaprompt.md` or `06-super-prompt-generic.md`.
3. When using specific stacks (FastAPI, React, ML, etc.), include the matching file from `04-stack-profiles/`.
4. If you are in Cursor, merge `05-cursor-rules/cursorrules-global.jsonc` into your `.cursorrules`.
5. For special environments:
   - Claude: see `09-claude-project-system-prompt.md`
   - Gemini / ChatGPT: see `10-gemini-openai-system-instruction.md`
   - Obsidian: use `11-obsidian-template.md`
   - VS Code: use `12-vscode-project-template.md`
6. When you ask any model to create software, reference these rules and tell it to follow them strictly, then describe your project.
