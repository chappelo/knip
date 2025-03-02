---
title: Unsupported
---

This page is an overview of related features Knip does not support.

## Unused variables

Knip doesn't look for unused variables within a file. It only looks for values
and types that are imported and/or exported.

Use [ESLint][1], [Biome][2] or [oxc][3].

## Circular dependencies

Knip has no issues with circular dependencies, and does not report them. Tools
that do support this include [DPDM][4], [Madge][5] and [skott][6].

[1]: https://eslint.org
[2]: https://biomejs.dev
[3]: https://oxc.rs
[4]: https://github.com/acrazing/dpdm
[5]: https://github.com/pahen/madge
[6]: https://github.com/antoine-coulon/skott
