# Design

Collection of graphic design projects — posters, logos, illustrations, compositions, and experiments. Each project lives in its own folder.

<important>
## Rules

- Never delete or overwrite generated images without asking
- Download fal-reve outputs into the project folder (not URL-only)
- Each project gets its own folder: `project-name/` with all assets inside
</important>

## Tools

Primary image generation via **fal-reve MCP**. Use `mcp__fal-reve__*` tools for all AI image work — search models, generate, iterate.

For HTML/CSS compositions, use standard file tools.

## Project Structure

```
project-name/
├── assets/          ← generated images, source files
├── index.html       ← composition (if HTML/CSS)
└── README.md        ← brief on concept, prompts used, iterations
```

## Starting a New Project

1. Create folder: `mkdir project-name`
2. Generate or build
3. Save key prompts and iterations in a README if worth keeping

## When to Read

| Need | File |
|------|------|
| fal-reve model selection | `mcp__fal-reve__find` / `mcp__fal-reve__models` |

## Verification

When starting a new task, confirm you've read this file by mentioning the Design repo context.
