- Dev: `ghcid -r`
- Run: `cabal run`
- Build: `IN_NIX_SHELL= nix-build` (envvar needs to be empty because if build is started in nix-shell it will not work otherwise)

Add dependencies to `haskell-example-project.cabal` in the `build-depends` section and reload nix-shell/vs-code.

Start new project by adding `default.nix` and running `cabal init` after reloading nix-shell.
