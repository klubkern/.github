# Contributing to Klubkern

Thanks for helping. These rules apply to every repository of the organisation.

## Branches and releases

- Work happens on feature branches off `develop`.
- `develop` collects finished work. A merge from `develop` into `main` is a
  release and is done by the maintainers.
- Keep pull requests small: one logical change each.

## Commits

- [Conventional Commits](https://www.conventionalcommits.org/):
  `feat`, `fix`, `docs`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`.
- One logical change per commit. Squash `fixup!` commits before you push.

## Language

- Code, identifiers, comments, commit messages, pull requests and docs are in
  English.
- The product's user-facing text is German and English. It always goes
  through the translation files, never directly into the code.
- Each repository checks this automatically. A deliberate exception is marked
  on the line, as the check's message explains.

## Tests

New behaviour comes with tests, and a bug fix with a test that fails without
it. A pull request is reviewed once all checks are green.

## Security

Never open a public issue for a vulnerability. See [SECURITY.md](SECURITY.md).
