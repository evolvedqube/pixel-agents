# Pixel Agents plugin

The Claude Code plugin for the **Pixel Agents** macOS app. It lets the app show
your Claude Code sessions in its pixel-art office and surface permission
requests and questions in the notch island, so you can answer without
switching back to your terminal.

> This repository contains only the plugin. The Pixel Agents app is a separate
> Mac App Store download.

<!-- TODO before publishing: replace the line below with the live Mac App Store link. -->
**Get the app:** Pixel Agents on the Mac App Store — *link to be added on launch*

## Requirements

- The Pixel Agents app, installed and running
- Claude Code

## Install

1. Install and launch the Pixel Agents app.
2. In a Claude Code session, run:

```
/plugin marketplace add evolvedqube/pixel-agents
/plugin install pixel-agents@pixel-agents
```

3. Restart any already-running Claude Code sessions. New sessions are picked
   up automatically.

## Use it

1. Launch Pixel Agents.
2. Start a Claude Code session as usual — it appears in the app's office.
3. When Claude needs permission or asks a question, answer it in the notch
   island — or in your terminal, as before.

If the app isn't running, the plugin does nothing and Claude Code works
exactly as it does without it.

Privacy in one line: the plugin talks only to the Pixel Agents app on your
own Mac — nothing leaves your machine.

## Update

```
/plugin marketplace update pixel-agents
/plugin update pixel-agents@pixel-agents
```

Then restart your Claude Code sessions.

## Uninstall

```
/plugin uninstall pixel-agents@pixel-agents
/plugin marketplace remove pixel-agents
```

## Troubleshooting

- **Sessions don't show up** — make sure the app is running, then restart the
  Claude Code session.
- **Install failed** — run `/plugin marketplace update pixel-agents` and try
  installing again.
- **Still stuck?** Open an issue at
  <https://github.com/evolvedqube/pixel-agents/issues> — please don't include
  sensitive prompts, code, or file paths.

## License

MIT for the plugin in this repository — see [LICENSE](LICENSE). The Pixel
Agents macOS app is a separate, proprietary product and is not covered by it.

Claude and Claude Code are trademarks of Anthropic. This is an independent
project, not affiliated with Anthropic.
