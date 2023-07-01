# ClojureScript Template

This is a template for a project using ClojureScript via `shadow-cljs`

## Connect to REPL via Conjure

- `yarn dev`
  - Starts the REPL server
- Make sure a browser context is available by opening your project
    in-browser
- Open Neovim
  - Conjure should automatically connect to the REPL
- In Neovim, run `:ConjureShadowSelect app` to connect to the correct
    context
- In Neovim, run `:ConjureEval` on whatever expression you'd like to
    evaluate

Once you start Neovim, Conjure should autoconnect to your repl
