# Using Submodules

The `submodules/` package should never contain anything more than this document and `git submodule` references to parts of Project[0].
Each submodule listed here is expected to provide an `index.md` in the git root if they wish to have their documentation subsumed and crosslinked here.

## Adding Submodules

This should be as simple as running `git submodule add https://github.com/<path>/<to>/<project>.git`.  Once that is done, you'll need to add a link in `/docs/index.md` in order to pick up changes.