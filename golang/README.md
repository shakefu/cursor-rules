# Go Development Rules

This directory contains a comprehensive collection of modern Go development
guidelines, freshly updated with Anthropic's prompt engineering best practices
(now with 100% less Python AND 100% less shouty imperatives!).

Each rule file has been enhanced with idiomatic Go examples, clear rationales,
and actionable guidance that actually helps you write better Go code.

## Rule Files

### Core Guidelines

- [**General**](./golang-general.mdc): Core interaction principles and communication
  patterns for effective AI assistance
- [**Development**](./golang-development.mdc): Modern Go development with comprehensive
  examples, concurrency patterns, and best practices

### Testing & Quality

- [**Testing**](./golang-testing.mdc): BDD-style testing with Ginkgo/Gomega, including
  advanced patterns and practical examples
- [**Version Control**](./golang-version-control.mdc): Git workflows with conventional
  commits and Go-specific patterns

### Build & Deployment

- [**GitHub Actions**](./golang-github-actions.mdc): Complete CI/CD workflows with
  Go-specific tooling, security scanning, and cross-platform builds
- [**Module Management**](./golang-module-management.mdc): Comprehensive Go module
  management including workspaces, private modules, and publishing

### Documentation & Management

- [**Markdown Documentation**](./golang-markdown-documentation.mdc): Documentation
  best practices integrating with `go doc` and Go conventions
- [**Version Management**](./golang-version-management.mdc): Dependency management,
  semantic versioning, and security scanning with Go tools

## What Makes These Rules Special

Each rule file includes:

- **Clear rationales** explaining why guidelines matter for Go projects
- **Idiomatic Go examples** showing proper patterns and anti-patterns
- **Complete workflows** from module init to production deployment
- **Security considerations** using `govulncheck` and other Go security tools
- **Concurrency guidance** for goroutines, channels, and race detection
- **AI collaboration tips** for effective Go pair programming
- **Conversational tone** that's helpful rather than intimidating

These aren't just rules—they're your gopher-approved guidelines for building
robust, maintainable Go projects with modern tooling and community best practices.
