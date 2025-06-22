<!-- markdownlint-disable MD013 -->

# cursor-rules

_A veritable compendium of coding commandments for the modern Cursor IDE user – because no one expects the Spanish Inquisition to do their code review._

## What is this?

`cursor-rules` is a living collection of opinionated (and occasionally cheeky) guidelines, lint-able lore, and workflow wisdom for day-to-day software development inside the [Cursor](https://cursor.sh) IDE. Think of it as an encyclopedia of best practices that you can copy-and-paste (or, better yet, programmatically ingest) into your projects, CI, or AI assistants so that your codebase remains _mostly harmless_.

> "This README was forged in the fires of PEP 8, cooled in the lake of Ruff, and polished by the Knights who say _ni!_" – **Someone probably**

### Why keep rules in a repo?

1. **Single source of truth** – avoid the _Dead Parrot_ problem where guidelines live in a forgotten wiki page and quietly expire.
2. **Version control** – rules evolve; commits make that evolution explicit.
3. **Reuse & automation** – having rules in machine-readable Markdown allows linters, bots, and AI copilots (hello there!) to enforce or surface them.

## Directory tour (bring your own coconut halves)

| Path          | What you will find                                                                     | Notable quotes                                         |
| ------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| `python/`     | A gaggle of `*.mdc` files that cover Python development, testing, packaging, and more. | "It's only a flesh wound!" (about ignoring type hints) |
| `script/docs` | A tiny helper that politely reminds you there is _no_ generated documentation... yet.  | "We're on a mission from Godot."                       |
| `.github/`    | Workflows, issue templates, and other GitHub accoutrements.                            | "And now for something completely CI."                 |

_(If you were looking for the Holy Grail, try `find . -name shrubbery` – we don't have one either.)_

## Quick start

```bash
# Clone the repository (or swallow it like an African swallow)
$ git clone https://github.com/your-org/cursor-rules.git

# Read a rule file (mind the whitespace)
$ bat python/python-development.mdc
```

Need to integrate these rules into your own project? Copy the relevant `*.mdc` files, link to them from your docs, or turn them into linting rules for your favourite tooling. Contributions are welcome – but remember to sign the **Commitment to Silly Walks** (a.k.a. follow Conventional Commits).

## Contributing

1. Fork → clone → branch (no lobsters).
2. Add or update a rule file.
3. Run `pre-commit run --all-files` to appease the style gods.
4. Create a pull request and wait for _The Bridgekeeper_ (CI) to ask three questions of you.

If you think a rule is too strict, open an issue and bring your finest arguments (or a shrubbery). We listen.

## License

Released under the MIT License. Feel free to reuse, remix, and quote at parties – just don't mention the war.
