<div align="center">

<img src="docs/assets/logo/launchkey.png" width="88" height="88" alt="">

# LaunchKey

**The starting point for every full-stack app I build next.**

One Bun monorepo with the stack, the tooling, and the auth already wired up.<br>
Clone it, rename it, and spend day one on your product instead of your setup.

![Runtime: Bun](https://img.shields.io/badge/runtime-Bun-f9f1e1?logo=bun&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Effect](https://img.shields.io/badge/Effect-111111)
![TanStack Start](https://img.shields.io/badge/TanStack_Start-FF4154)
![Better Auth](https://img.shields.io/badge/Better_Auth-000000)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?logo=turborepo&logoColor=white)
![Status: rebuilding](https://img.shields.io/badge/status-rebuilding-orange)

</div>

## Why

Every new project starts the same way: pick a runtime, set up a monorepo, wire a linter and a formatter, add auth, and decide how errors and state flow through the app. That work takes days, and none of it is the product.

LaunchKey makes those decisions once. A new app starts from a repository that already builds, tests, and signs users in.

## The stack

| Layer          | Choice                                                                                |
| -------------- | ------------------------------------------------------------------------------------- |
| Runtime        | [Bun](https://bun.sh)                                                                 |
| Monorepo       | [Turborepo](https://turbo.build)                                                      |
| Language       | [TypeScript](https://www.typescriptlang.org)                                          |
| Core library   | [Effect](https://effect.website)                                                      |
| Web framework  | [TanStack Start](https://tanstack.com/start)                                          |
| State          | [Effect Atom](https://github.com/tim-smart/effect-atom)                               |
| Forms          | Effect Form                                                                           |
| Authentication | [Better Auth](https://www.better-auth.com)                                             |
| Lint and format | [Oxlint](https://oxc.rs/docs/guide/usage/linter) and [Oxfmt](https://oxc.rs/docs/guide/usage/formatter) |

## Status

LaunchKey is being rebuilt from an empty repository. The stack above is the plan. Setup instructions arrive with the first runnable app.
