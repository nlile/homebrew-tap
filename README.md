# nlile Homebrew Tap

This tap ships the unified `synth` cask.

The legacy `synth-harbor` cask is disabled as of 2026-07-16 and points users
to `synth`.

Install:

```bash
brew tap nlile/tap
brew install --cask synth
```

If you still have the old Harbor-only alpha installed:

```bash
brew uninstall --cask synth-harbor
brew install --cask synth
```
