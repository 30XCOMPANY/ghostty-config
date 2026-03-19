# Ghostty Config

Opinionated Ghostty terminal configuration. Designed to disappear.

- **Font**: Maple Mono NF CN (ligatures + CJK + Nerd Font)
- **Theme**: Catppuccin (auto light/dark)
- **Window**: macOS glass blur, transparent titlebar, 88% opacity
- **Navigation**: home-row splits (`Cmd+Alt+hjkl`), resize (`Cmd+Ctrl+hjkl`)
- **Quick Terminal**: `Ctrl+`` drop-down from top
- **Claude Code**: 160×50 window, link detection, 10M scrollback

## One-Click Setup

Copy the prompt below and paste it into [Claude Code](https://claude.ai/claude-code) or [Codex](https://github.com/openai/codex):

```
Install Ghostty terminal with my config from GitHub.

Steps:
1. Install Ghostty if not present (brew install --cask ghostty)
2. Install the font "Maple Mono NF CN" (brew install --cask font-maple-mono-nf-cn)
3. Clone config: git clone https://github.com/30XCOMPANY/ghostty-config.git ~/.config/ghostty
   - If ~/.config/ghostty already exists, back it up first to ~/.config/ghostty.bak
4. Verify: ls ~/.config/ghostty/config

That's it. Open Ghostty and everything should work.
```

## Keybindings

| Action | Keys |
|---|---|
| New tab | `Cmd+T` |
| Jump to tab N | `Cmd+1-9` |
| Split right / down | `Cmd+D` / `Cmd+Shift+D` |
| Navigate splits | `Cmd+Alt+H/J/K/L` |
| Resize splits | `Cmd+Ctrl+H/J/K/L` |
| Equalize splits | `Cmd+Shift+E` |
| Zoom split | `Cmd+Shift+F` |
| Quick terminal | `Ctrl+`` ` |
| Float on top | `Cmd+Ctrl+T` |
| Reload config | `Cmd+Shift+,` |
