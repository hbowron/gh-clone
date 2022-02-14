# gh clone

[GitHub CLI] extension for Github repo organization.

By default clones repositories to `$HOME/src/github.com/<org>/<repo>`.

## Install

Make sure you have version 2.0 or [newer] of the [GitHub CLI] installed.

```bash
gh extension install hbowron/gh-clone
```

### Upgrade

The `gh extension list` command shows if updates are available for extensions. To upgrade, you can use the `gh extension upgrade` command:

```bash
gh extension upgrade hbowron/gh-clone

# Or upgrade all extensions:
gh extension upgrade --all
```

## Configuration

```bash
# default
$GITHUB_DIR="$HOME/src/github.com"
```

## Commands

`gh clone <org>/<repo>`