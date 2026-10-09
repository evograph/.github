<p align="left">
  <a href="https://evograph.app"><img src="https://raw.githubusercontent.com/evograph/.github/main/profile/assets/evograph.png" width="80" height="80" alt="Evograph"></a>
</p>

# Keep the reasoning behind your code.

Evograph records the **problems, decisions, notes, and changes** behind a codebase as a local, connected graph. Keep that context in your repository, review it with your code, and give coding agents a clearer starting point.

[Explore Evograph](https://evograph.app) · [Read the docs](https://evograph.app/docs) · [Try the interactive example](https://evograph.app/demo)

## Start with your repository

Requires **Node.js 22.12+** and npm.

```sh
npm install -g @evograph/cli
cd your-repository
ecs init
ecs create
ecs graph
```

Records live in `.evolution/` alongside your project. Link a decision to the problem it solves, connect the implementation, and follow the reasoning when the code changes again.

For coding agents, `ecs context` prints the graph context. `ecs init --agents codex,claude,cursor` generates instruction files for supported tools. See the [agent workflow](https://evograph.app/docs/agents).

## Build with us

| Repository | What lives here |
| --- | --- |
| [cli](https://github.com/evograph/cli) | The TypeScript CLI, local graph storage, Git linking, and agent instructions. |
| [docs](https://github.com/evograph/docs) | The Next.js website, documentation, and interactive example. |

Evograph is an **early release**. Try it on a project and tell us where the workflow helps or gets in your way. [Report a CLI issue](https://github.com/evograph/cli/issues) or follow the [contributing guide](https://github.com/evograph/cli/blob/main/CONTRIBUTING.md).

Created and maintained by [Muhammad Atif](https://github.com/acefolioDev). [Contact](https://evograph.app/contact).
