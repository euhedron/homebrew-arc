# homebrew-arc

The Homebrew tap for **[arc](https://github.com/euhedron/arclite)** — an agent-first CLI for AI-powered cross-repo code intelligence and auditing, by [Euhedron](https://euhedron.com).

```sh
brew install euhedron/arc/arc
```

Upgrades: `brew upgrade euhedron/arc/arc` (a brew-installed arc detects itself and points `arc update --apply` here rather than self-replacing the keg).

The formula installs the per-platform binary published on arclite's [GitHub Releases](https://github.com/euhedron/arclite/releases) (macOS arm64/x86_64, Linux x86_64/arm64). `Formula/arc.rb` is **generated** by [`bump.sh`](bump.sh) — the template lives there, and arclite's release workflow invokes it on each release (checksums from the release's `SHA256SUMS`), so this tap tracks releases without hand edits.
