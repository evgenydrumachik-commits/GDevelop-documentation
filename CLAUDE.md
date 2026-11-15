# Important Writing Style And Architecture Constraints

## Home policy loading

At task start, use an existing authorized private, read-only GitHub route to resolve Home `refs/heads/main` to one full SHA. Read `BOOTSTRAP.md`, `policies/core.md`, and applicable modules at that SHA; verify Git blob SHA and SHA-256 for each file; resolve `main` again and use only an unchanged snapshot. Never copy private Home policy bytes or catalogs into this public repository. If this client cannot read current Home, preserve local writing rules, state that Home was not loaded, and do only independent work.

- Do NOT document non-user-facing implementation details. Focus only on information
  that is relevant to users creating games with GDevelop, not internal engine behavior.
- Do NOT list all actions/conditions in a list or table: the reference documentations are already
  automatically generated for this.
- Do not specify the default values. Don't feel forced to list all the properties of a
  behavior/object/condition/action: prefer to explain use cases, examples and how it's useful
  for the end user which will create a game with it.
- Do not explain standard default/shortcuts (the UI is supposed to make this clear already).
