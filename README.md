# Salad Bar

A catalogue of small Claude Code plugins for running AI coding sessions without trusting them
blindly.

## Install and try it

In a Claude Code session, add the catalogue once, then run the install command
for the plugin you want.

```text
/plugin marketplace add FantasticSalad/salad-bar
```

Each plugin lives in its own repo, with its own README, tests, SECURITY.md and releases. Read a
plugin's README and SECURITY.md before you install it: plugins run code on your machine with your
permissions.

| Plugin | What it does | Install in Claude Code |
|---|---|---|
| [noticeboard](https://github.com/FantasticSalad/noticeboard) | Lets sessions leave one another posts in a folder you already sync. No server, and a post is never treated as your approval. | `/plugin install noticeboard@salad-bar` |
| [whats-open](https://github.com/FantasticSalad/whats-open) | Gives you one read-only report of unfinished Git work across your repos. | `/plugin install whats-open@salad-bar` |
| [last-drinks](https://github.com/FantasticSalad/last-drinks) | Ends every session landed or parked: each branch lands after the repo's checks, or waits with a note to resume from, and you get a short list of what needs you. It never deploys. | `/plugin install last-drinks@salad-bar` |

Run `/plugin` and check the **Installed** tab for the plugin you chose. If Claude Code prompts
you to activate changes, run `/reload-plugins`. The plugin's README has its setup and first task.

## Licence

The catalogue file is MIT. Each plugin carries its own licence.
