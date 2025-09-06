# dollar-agent (`$` command)

Turn the forgotten `$` prefix into something useful: run your shell commands _with_ an AI agent.  
Think of it like how **jQuery** claimed `$` early on — now your terminal gets its own `$`.

## Requirements

- [Claude Code](https://github.com/anthropics/claude-code)

## Installation

```bash
npm install -g dollar-agent
```

This installs a global `$` command.

## Usage

Regular shell:

```bash
npm test
```

With `$` agent:

```bash
$ npm test
```

→ sends `npm test` to Claude Code, so you can run and discuss commands interactively.
[![Image from Gyazo](https://i.gyazo.com/95edfdf6ad026d85ef672790fb54ced6.png)](https://gyazo.com/95edfdf6ad026d85ef672790fb54ced6)

## Why `$`?

People often paste commands with a leading `$`, and the shell errors because no `$` command exists.
Now, just like **jQuery** made `$` the universal shortcut in JavaScript, you can make `$` your shortcut to an AI agent in the terminal.
[![Image from Gyazo](https://i.gyazo.com/72a09b7d1f786619ca3ea1f34e20e2b4.png)](https://gyazo.com/72a09b7d1f786619ca3ea1f34e20e2b4)

## Note

It’s a [tiny joke-like program](https://github.com/hata6502/dollar-agent/blob/main/index.sh) (just a few lines of Bash),
but surprisingly **practical** for everyday use.
