# tagoro9 Tap

Custom Homebrew tap for tagoro9-maintained formulae.

## Quick Start

Install directly:

`brew install tagoro9/tap/<formula>`

Or add the tap first:

`brew tap tagoro9/tap`
`brew install <formula>`

Or via a `brew bundle` `Brewfile`:

```ruby
tap "tagoro9/tap"
brew "<formula>"
```

## Formulae

Formulae live in the `Formula/` directory.

If this directory is empty, there are no published formulae yet.

## Maintenance

When adding or updating a formula:

- Add or edit the formula file in `Formula/`.
- Run `brew audit --strict <formula>` before publishing.
- Run `brew style <formula>` to keep formatting consistent.

## Documentation

`brew help`, `man brew`, or Homebrew’s official documentation at `https://docs.brew.sh`.
