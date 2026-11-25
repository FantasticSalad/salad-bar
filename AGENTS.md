# Repository work

This repo is a catalogue: `.claude-plugin/marketplace.json` lists plugins that each live in their
own repo, with their own code, tests and security notes. Nothing here runs.

Work on a branch, never directly on the default branch. Run `claude plugin validate --strict .`
after any change to the marketplace file. List a plugin only once its own repo is public.

Everything outside `docs/internal` must be fit to publish at every commit: no personal names,
paths, machines or private repository names. `bash tests/public-scan.sh` checks it. Public files
never link into `docs/internal`.
