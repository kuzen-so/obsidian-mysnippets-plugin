# MySnippets

MySnippets is an [Obsidian](https://obsidian.md) plugin that adds a status bar menu allowing you to quickly toggle your CSS snippets on and off.

Original plugin by [Chetachi Ezikeuzor](https://github.com/chetachiezikeuzor). This fork contains compatibility fixes for newer Obsidian versions.

## What's Fixed

The original plugin (v1.2.3) no longer works on Obsidian 0.16+ / 1.x due to API changes. This fork fixes:

- **Snippet creation fails**: `app.vault` reference error in the create modal
- **Menu doesn't open**: `setUseNativeMenu` method may not exist on newer platforms
- **Toggle/click broken**: Event bubbling causes menu to close unexpectedly when clicking toggle switches or buttons

## How to Install

### Manual

1. Download the latest release from the [Releases](https://github.com/kuzen-so/obsidian-mysnippets-plugin/releases) page
2. Extract the zip to your vault's `.obsidian/plugins/mysnippets-plugin/` folder
3. Enable the plugin in Obsidian Settings → Community Plugins

### BRAT

1. Install the [BRAT](https://github.com/TfTHacker/obsidian42-brat) plugin
2. Add `https://github.com/kuzen-so/obsidian-mysnippets-plugin`

## Features

- Toggle CSS snippets from the status bar
- Create new snippets with a built-in editor
- Reload snippets without restarting Obsidian
- Open snippets folder directly
- Configurable settings (glass menu effect, auto-open new snippets, default CSS template)

## License

This fork retains the original author's license. See the original repository for full license details.
