# Micromega plugin

[![GitHub CI][gh-badge]][gh-link]

[gh-badge]: https://github.com/proux01/micromega-plugin/actions/workflows/nix-action-rocq-master.yml/badge.svg
[gh-link]: https://github.com/proux01/micromega-plugin/actions/workflows/nix-action-rocq-master.yml

The Micromega plugin is a plugin for the Rocq Prover providing
(semi)decision procedures for arithmetic.
End users can use it through tactics like `lra` in libraries using the plugin.

## Installation

Information on how to build and install from sources can be found in
[`INSTALL.md`](INSTALL.md).

## Documentation

Please refer to the libraries documentation for how to use the tactics.
Library developers can look at the comments in the `theories/*.v` files,
for instance starting with `theories/checker.v`.

## Bug reports

Please report any bug / feature request in [our issue tracker](https://github.com/rocq-community/micromega-plugin/issues).

To be effective, bug reports should mention the OCaml version used
to compile and run Rocq, the Rocq version (`rocq -v`)
and include a complete source example leading to the bug.
