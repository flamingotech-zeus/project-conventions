# Project Conventions

[English](README.md) | [简体中文](README.zh-CN.md)

> Two mandatory rules that apply automatically when a project is created or initialised, so they do not have to be restated every time.

## What this is

This is not a style guide and it is not a list of preferences. There are exactly two rules, both of them there because breaking them caused real trouble.

The value is in the constraint. A convention file with thirty rules gets ignored. Two rules that are always applied actually change what happens.

## Why we open-sourced it

Every new project started with the same two corrections being made. Rather than keep making them, we wrote them down as rules that apply on their own.

There is nothing of ours inside — the rules are about how to work, not what to build. It is the most portable thing in this collection.

## What it does

- **Rule 1 — official sources only.** Facts, data, specifications and tool behaviour may be taken only from official documentation, official repositories, official announcements, or standards bodies and government sources. Personal blogs, forums, Q&A sites, unofficial reposts and marketing copy are not admissible as evidence.
- **Rule 2 — classify, then index.** Create directories by category as the project is set up, and generate a structure document at the project root so the layout can be seen at a glance instead of by drilling into trees.

## Requirements

None — convention only, no scripts

## Installation

```bash
git clone https://github.com/<your-username>/project-conventions.git
```

Then place the folder into your agent skills directory:

| OS | Path |
|---|---|
| Windows | `C:\Users\<you>\.workbuddy\skills\project-conventions\` |
| macOS / Linux | `~/.workbuddy/skills/project-conventions/` |

There is no build step. Restart the session and it takes effect.

## How to use

It applies on its own whenever a project is created or work begins in an empty directory. You can also trigger it explicitly:

- "Initialise this project"
- "Set up the directory structure"
- "New project"

The skill creates the classified layout and writes the root index document.

## Files

```
└── SKILL.md
```

## Notes and limits

1. **Deliberately short.** Two rules get followed; a longer list gets skimmed. Adding more should be resisted.
2. **Rule 1 is the load-bearing one.** Most incorrect conclusions trace back to a secondary source that looked authoritative. Insisting on primary sources removes a whole class of errors.
3. **Rule 2 is about navigation, not tidiness.** The index exists so the project can be understood without opening the tree.
4. **Conventions are not enforcement.** Nothing stops a file from being dropped in the wrong place. The rules shape the default path, and defaults are what actually get used.

## License

MIT
