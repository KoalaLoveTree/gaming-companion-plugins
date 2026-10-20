# Gaming companion plugins

Plugins for the [gaming companion](https://github.com/KoalaLoveTree/gaming_companion). A plugin is a folder with `plugin.toml`. Plugins for one game sit together in a game folder. The app reads this directory. It does not fetch GitHub on its own.

Clone it and point the app at the clone:

```bash
GAMING_COMPANION_PLUGINS=/path/to/gaming-companion-plugins
```

Or keep the clone where the app already looks: `./plugins`, or `plugins` next to the executable.

## Arc Raiders

`arc-raiders` is one game. Each plugin is its own folder, so deleting a folder removes only that plugin.

- `loot` opens the loot sheet and a local notes page.
- `maps` opens the interactive maps at <https://arctracker.io/maps>.

