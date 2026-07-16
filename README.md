# nlile Homebrew Tap

This tap ships the unified `synth` cask.

`synth-harbor` is retained only as a deprecated migration path for old alpha
installs and points users to `synth`.

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
