# docgen-action sandbox

Throwaway repository. It exercises test branches of
[marcelolynch/docgen-action](https://github.com/marcelolynch/docgen-action)
before the changes are proposed upstream to
[leanprover-community/docgen-action](https://github.com/leanprover-community/docgen-action).

- `docs/Gemfile` and `docs/Gemfile.lock` come from emilyriehl/infinity-cosmos (after emilyriehl/infinity-cosmos#214).
- `fixtures/Gemfile.lock.stale` is the pre-#214 lockfile (nokogiri 1.13.6), which fails on Ruby 3.4.
