# Contributing to clean-sweep

Thanks for contributing! Every PR counts. 🚀

## Ways to Contribute

- 🐛 Bug reports — [bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md)
- 💡 Feature ideas — [feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md)
- 💻 Code — read on
- 🌐 Translations — copy `resources/strings.json`, translate values, open PR

## Development Setup

```powershell
git clone https://github.com/yourname/clean-sweep.git
cd clean-sweep
```

Build & test instructions are language-specific and live in `docs/installation.md` (dev section).

## Pull Request Rules

1. One feature or fix per PR — small PRs merge fast
2. Branch naming: `feature/x`, `fix/y`, `docs/z`
3. All CI checks must pass
4. Update CHANGELOG.md under `Unreleased`
5. Link the issue (`Fixes #123`)
6. Conventional Commits for titles: `feat(scope): ...`

## Code Style

- Keep functions small; no raw new/delete (C++ projects)
- Check return values on OS API calls
- User-facing strings via i18n resource file
- Run the formatter before pushing

## Code of Conduct

By participating you agree to the [Code of Conduct](CODE_OF_CONDUCT.md).
