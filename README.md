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
# if you want to change the default clone directory
export GH_CLONE_DEFAULT_DIR="$HOME/src/github.com"

# if you want to set a default organization
export GH_CLONE_DEFAULT_ORG="kubernetes"
# `gh clone cloud-provider-aws` will clone github.com/kubernetes/cloud-provider-aws
```

## Commands

`gh clone <org>/<repo>`
