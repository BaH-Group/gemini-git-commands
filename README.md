# Gemini Git Commands

This repository contains custom command definitions for the [Gemini CLI](https://github.com/google/gemini-cli) to streamline Git workflows.

## Commands

### `add`
Stage changes in your repository.
- **Usage**: `/git:add` (stages all changes) or `/git:add <file-path>` (stages specific files).

### `commit`
Generate a concise, descriptive commit message based on your currently staged changes.
- **Usage**: `/git:commit`

### `push`
Push the current branch to the `origin` remote.
- **Usage**: `/git:push`

## Installation

To install these commands globally, run:

```bash
cp -r .gemini/commands/git ~/.gemini/commands/git
```

Alternatively, ensure they are located in your `.gemini/commands/git/` directory within your project.
