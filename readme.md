- Dev: `ghcid --test=main`
- Run: `cabal run`
- Build: `nix-build`

Add dependencies to `haskell-example-project.cabal` in the `build-depends` section and reload nix-shell/vs-code.

Start new project by adding `default.nix` and running `cabal init` after reloading nix-shell.
