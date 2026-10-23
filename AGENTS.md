> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}

## CodeRabbit

This repo is covered by CodeRabbit (free open-source plan). Its settings come from the shared config in [`cfdude/coderabbit`](https://github.com/cfdude/coderabbit); a `.coderabbit.yaml` in this repo replaces it entirely unless that file starts with `inheritance: true`.

- **Opening a PR:** CodeRabbit reviews it automatically. Read its comments (`gh pr view --comments`, or `coderabbit pullrequest <number-or-url> --show-threads --agent`) and fix them before merging.
- **Committing straight to `main` with no PR:** nothing reviews it, so run `coderabbit review --agent --gate major` first and fix what it finds. The CLI has an hourly allowance of included reviews (check with `coderabbit usage`), so use it on demand, not in a pre-commit hook.
