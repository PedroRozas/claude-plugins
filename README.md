# Claude Code plugins

Plugins for [Claude Code](https://code.claude.com) by Pedro Rozas. Add the marketplace once and install any of them.

```text
/plugin marketplace add PedroRozas/claude-plugins
/plugin install git-guard@pedrorozas
/plugin install agent-board@pedrorozas
/plugin install orphans@pedrorozas
/plugin install ship-ready@pedrorozas
```

Or install one directly and answer `y` when asked to add the marketplace:

```text
/plugin install git-guard --marketplace PedroRozas/claude-plugins
```

From a shell, use `claude plugin marketplace add` and `claude plugin install` with the same arguments. In the desktop app, click **+** next to the prompt box, then **Plugins**, **Add marketplace** with `PedroRozas/claude-plugins`, then **Add plugin**.

| Plugin | What it does |
| --- | --- |
| [git-guard](https://github.com/PedroRozas/git-guard) | Stops the agent from committing, pushing or opening PRs unless you grant a counted, expiring permission, and checks commit messages |
| [agent-board](https://github.com/PedroRozas/agent-board) | A live board of your Claude Code sessions, their subagents, activity and token usage |
| [orphans](https://github.com/PedroRozas/orphans) | Finds the processes Claude left running, asks the session whether it still needs them, and ends them when the session ends |
| [ship-ready](https://github.com/PedroRozas/ship-ready) | Checks whether a Claude Code plugin idea is worth building, then ships it with README, license, changelog, CI, GitHub release and marketplace entry |

Each plugin keeps its own repository, issues and releases; this one only lists them.

## License

MIT
