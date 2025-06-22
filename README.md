# cursor-rules

A curated collection of development guidelines and best practices for modern
software development with the Cursor IDE.

_Because sometimes even the best developers need a gentle reminder that yes,
you do need to write tests._

## What is this?

`cursor-rules` is a comprehensive set of coding standards, workflow patterns,
and development guidelines designed to improve code quality and team
collaboration. These rules can be integrated into your projects, CI/CD
pipelines, and development tools to maintain consistency across your codebase.

The guidelines are stored as machine-readable Markdown files, making them easy
to version, share, and automate. Think of it as a very polite robot that
reminds you to format your code properly.

### Why keep rules in a repository?

1. **Centralized standards** – maintain a single source of truth for your
   development practices (because we all know what happens when standards live
   in Slack threads)
2. **Version control** – track changes to your guidelines over time with full
   history
3. **Automation ready** – integrate with linters, CI systems, and development
   tools
4. **Team alignment** – ensure everyone follows the same standards, reducing
   the ancient art of "but it works on my machine"

## Directory structure

| Path          | Contents                                                  |
| ------------- | --------------------------------------------------------- |
| `python/`     | Python-specific guidelines covering development, testing, |
|               | and packaging                                             |
| `script/docs` | Documentation utilities and helpers (spoiler: there's not |
|               | much here yet)                                            |
| `.github/`    | GitHub workflows, issue templates, and repository         |
|               | configuration                                             |

## Quick start

```bash
# Clone the repository
git clone https://github.com/your-org/cursor-rules.git

# Browse the guidelines (exciting stuff, really)
ls python/
cat python/python-development.mdc
```

To integrate these rules into your project:

1. Copy relevant `.mdc` files to your project documentation
2. Reference them in your project's contributing guidelines
3. Configure your linting tools to enforce the standards
4. Add them to your CI/CD pipeline for automated checking
5. Watch as your code mysteriously becomes more readable

## Contributing

We welcome contributions to improve and expand these guidelines:

1. **Fork and clone** the repository
2. **Create a feature branch** for your changes
3. **Add or update** rule files following our formatting standards
4. **Test your changes** by running `pre-commit run --all-files` (yes, we eat
   our own dog food)
5. **Submit a pull request** with a clear description of your changes

For significant changes, please open an issue first to discuss the proposed
modifications. We promise to be more diplomatic than your average code
reviewer.

## License

This project is licensed under the MIT License. You're free to use, modify,
and distribute these guidelines in your own projects. Just remember us when
you're famous.
