# LogiShell

**LogiShell** (also written **Logi Shell**) is one working shell for the age of AI.
It wraps any model and any harness behind a single workspace: local models for
private and light work, cloud models for heavy work, always on your own keys and
with no vendor lock.

- CLI: <https://lsh.dev>
- Site: <https://logishell.com>
- What an AI shell is: <https://logishell.com/ai-shell/>
- Docs: <https://docs.logishell.com>
- Package: <https://www.npmjs.com/package/logishell>

## `lsh`: the public CLI

Point it at a repository and get a map an agent can read.

```bash
curl -fsSL lsh.dev | sh
npx logishell scan .
lsh scan . --open
```

`--open` prints the same markdown on stdout and opens the report in a browser.

## What lives here

This repository is the public home: README, issues and CLI binaries. Product
sources (shell, runner, kernel) stay in a private tree. Binaries in Releases are
the same bytes as <https://dl.logishell.com/cli/>.

If the scan helped, star this repo so other people can find it.
