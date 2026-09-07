# Arsh Ghotra

AI and Data Solutions Engineer. I build automation systems around language
models and developer tools, mostly in Python.

## Now

**[build-your-own-agent](https://github.com/idk-arsh/build-your-own-agent)**,
an AI agent from scratch in twelve chapters. One Python file per chapter, each
under 200 lines, standard library only. Every chapter runs in CI against a mock
Messages API server, so a fork's pull request gets the full suite without a key.
Chapters 1 to 4 are done: the loop, tools, error recovery, loop control with a
real dollar cap. In progress in the open.

**[claude-code-windows-kit](https://github.com/idk-arsh/claude-code-windows-kit)**,
an English-language setup kit for Claude Code on Windows. Winget install script
that merges into your existing settings instead of overwriting them, a
permissions template tuned for a Windows dev, and four PowerShell hooks: a
secrets guard, a git guard that stops force pushes to main and `rm -rf` on
the tree, a format-on-edit hook, and a turn-end notifier. 269 test cases run
the hooks the way Claude Code does, under both PowerShell 5.1 and 7 in CI.

**[claude-skill-lint](https://github.com/idk-arsh/claude-skill-lint)**, a linter
for Claude Code and Agent Skills packages. Fifteen rules: frontmatter that
parses, keys the host actually knows, descriptions that will trigger, the
1,536-character listing cap, file references that exist, and a `--target`
switch that says what claude.ai will reject before you upload. Zero runtime
dependencies, Python 3.10 and up, runs in CI in under a second.

**[MultiTerm](https://github.com/idk-arsh/multiterm)**, a multi-pane terminal
workspace for Windows. Real shells over ConPTY, workspaces that remember which
folders a project needs and what each one runs, and broadcast typing to every
pane. Python and Tk, no Electron. Released, MIT licensed, downloadable as a
single exe.

## In progress

Two more repos, private until each is worth reading. They finish the story
that build-your-own-agent starts: learn how agents work, ship one, test it.

- A production agent starter kit: FastAPI, Next.js, streaming, MCP, auth,
  Docker. Public once it boots from a clean clone with one command.
- An evaluation and tracing toolkit for LLM agents and MCP servers, pytest
  native and local first. Public at the first PyPI release.

## Contact

[LinkedIn](https://www.linkedin.com/in/aghotra07/) · [Portfolio](https://portfolio-omega-steel-20.vercel.app/) · arsh9745774@gmail.com
