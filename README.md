# Collections of Custom Files for Various AI Products I have used.

# [Antigravity](https://antigravity.google/docs/get-started)

## Workspace

1. Common: `./agent/{rules,workflows,skills}/<file-or-folder>`
2. Rules: `./GEMINI.md`

## Global

1. Rules: `~/.gemini/GEMINI.md`
2. Workflows: `~/.gemini/antigravity/global_workflows/`
3. Skills: `~/.gemini/antigravity/skills/<folder>/`

# [Gemini CLI](https://geminicli.com/docs/get-started/configuration/#context-files-hierarchical-instructional-context)

## Workspace

1. Default context file: `./GEMINI.md`

## Global

1. Default context file: `~/.gemini/GEMINI.md`

# [Copilot in VSCode](https://code.visualstudio.com/docs/copilot/customization/overview)

## Workspace

1. Instructions:
  - Single file: `.github/copilot-instructions.md`. Applies to all chats.
  - Multiple files: `.github/instructions/*.instructions.md`. Applies to files-specific.
  - For multiple agents: `./AGENTS.md`. Applies to multiple agents. Supports nested `AGENTS.md`.
2. Prompt files: `.github/prompts/<file>`
3. Agents: `.github/agents /*.agent.md`
3. Skills: `.github/skills/<folder>/`

## Global(User)

> Supports: Instructions/Prompt

In the Chat view, select Configure Chat (gear icon) > {Supports}, and then select New {instruction file, prompt file}. Alternatively, type `Chat: {Supports}` from the Command Palette (Ctrl+Shift+P) to select the appropriate command.