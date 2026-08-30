# LogiShell

`lsh` is a CLI. Point it at a repository, get a map an agent can read.

```bash
npx logishell scan .
curl -fsSL https://logishell.com/lsh.sh | sh
lsh scan . --open
```

`--open` prints the same markdown on stdout and opens the report in a browser.

This repository is the public home: README, issues, and CLI binaries. Product sources (IDE, runner, kernel) stay in a private tree. Binaries in Releases are the same bytes as `https://dl.logishell.com/cli/`.

If the scan helped, star this repo so other people can find it.
