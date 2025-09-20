# dollar-agent (`$` command)

Turn the forgotten `$` prefix into something useful: run your shell commands _with_ an AI agent.  
Think of it like how **jQuery** claimed `$` early on — now your terminal gets its own `$`.

## Requirements

- [Codex CLI](https://github.com/openai/codex)

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

→ sends `npm test` to Codex, so you can run and discuss commands interactively.
[![Image from Gyazo](https://i.gyazo.com/cef92bb4721a5bc9ee66374eb7ca5d88.png)](https://gyazo.com/cef92bb4721a5bc9ee66374eb7ca5d88)

## Why `$`?

People often paste commands with a leading `$`, and the shell errors because no `$` command exists.
Even if you leave the `$` prefix on a command by mistake, the AI agent gently walks you through what to run.

[![Image from Gyazo](https://i.gyazo.com/72a09b7d1f786619ca3ea1f34e20e2b4.png)](https://gyazo.com/72a09b7d1f786619ca3ea1f34e20e2b4)

## Note

It’s a [tiny joke-like program](https://github.com/hata6502/dollar-agent/blob/main/index.sh) (just a few lines of Bash),
but surprisingly **practical** for everyday use.
