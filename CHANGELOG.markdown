0.2.3.1
-------
* Fix compilation with `hashable-1.2.5.0`
* Revamp `Setup.hs` to use `cabal-doctest`. This makes it build
  with `Cabal-1.25`, and makes the `doctest`s work with `cabal new-build` and
  sandboxes.

0.2.3
-----
* ghc 8 support
* `transformers` 0.5 support
* Removed redundant constraints on default definitions.

0.2.2
-----
* Removed spurious `generic-deriving` dependency
* Compiles warning-free on GHC 7.10

0.2.1
-----
* Support `bifunctors` 5

0.2
---
* Converted to `bifunctors` 4

0.1.1
-----
* Marked this package `Trustworthy`

0.1.0.1
-------
* Bumped dependency bounds for `generic-deriving`.

0.1
---
* Split from [https://github.com/analytics/hash](hash)
