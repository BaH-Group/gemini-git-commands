# Gemini Git Commands Extension

This repository is a [Gemini CLI](https://github.com/google/gemini-cli) extension that provides custom commands to streamline Git and Python workflows.

## Installation

To use this extension locally, clone the repository and link it:

```bash
git clone https://github.com/BaH/gemini-git-commands.git
cd gemini-git-commands
gemini extensions link .
```

## Commands

### Git Group

- **`git add`**: Stage changes.
  - Usage: `gemini git add` (stages all) or `gemini git add <path>`
- **`git commit`**: Generate a commit message from staged changes.
  - Usage: `gemini git commit`
- **`git push`**: Push to origin.
  - Usage: `gemini git push`

### Python Group

- **`python init`**: Scaffold a new Python project structure.
  - Usage: `gemini python init`

## Development

The commands are defined in the `commands/` directory as TOML files. The extension configuration is in `gemini-extension.json`.
