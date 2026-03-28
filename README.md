<p align="center">
  <img src="https://raw.githubusercontent.com/TheMax98000/gitsquid-releases/main/icon.png" width="128" alt="GitSquid">
</p>

<h1 align="center">GitSquid</h1>

<p align="center">
  <strong>A powerful free Git GUI client</strong><br>
  <em>The intuitive alternative to GitKraken</em>
</p>

<p align="center">
  <a href="https://github.com/TheMax98000/gitsquid-releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/TheMax98000/gitsquid-releases?style=flat-square&color=00bcd4" alt="Latest Release">
  </a>
  <img src="https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-58a6ff?style=flat-square" alt="Platforms">
  <img src="https://img.shields.io/badge/license-proprietary-768390?style=flat-square" alt="License">
</p>

---

## What is GitSquid?

GitSquid is a cross-platform Git GUI client built for developers who want the power of GitKraken without the aggressive pricing. Beautiful, fast, and packed with features.

<p align="center">
  <img src="https://raw.githubusercontent.com/TheMax98000/gitsquid-releases/main/screenshot.png" alt="GitSquid Screenshot" width="900">
</p>

## Features

### Core Git
- **Interactive commit graph** — Canvas-based with virtual scrolling, Gravatar avatars, branch coloring
- **Full git workflow** — Stage, unstage, commit (with amend), push, pull, fetch
- **Branch management** — Create, delete, rename, checkout, merge, rebase
- **Diff viewer** — Unified, split, and full file views with syntax highlighting
- **Git blame** — Inline blame with author, date, and click-to-select commit
- **Stash management** — Save, apply, pop, drop, visible on the graph
- **Tags** — Create, delete, push to remote
- **Cherry-pick, revert, reset** — Full context menu on commits
- **Conflict resolution** — Accept ours/theirs per file, 3-tab diff view
- **Auto-stash on checkout** — Automatically stash and reapply changes

### Integrations
- **GitHub, GitLab, BitBucket** — Connect via Personal Access Token
- **Pull Requests** — List, create, and open PRs directly from the app
- **Clone from provider** — Browse and search your remote repositories
- **Create remote repos** — Initialize and push to GitHub/GitLab/BitBucket

### Productivity
- **Multi-repo tabs** — Open multiple repositories, persisted across restarts
- **Integrated terminal** — Full terminal (xterm.js + node-pty) with `Cmd+``
- **Gitflow support** — Init, feature/release/hotfix start & finish
- **Submodules** — List, init, update, open in new tab
- **Profiles** — Switch between different Git identities and provider accounts
- **Graph search** — Filter commits by message, author, or hash (`Cmd+F`)

### UI & UX
- **Dark theme** — Professional developer-focused design
- **10 languages** — English, French, Spanish, German, Portuguese, Italian, Japanese, Chinese, Korean, Russian
- **Keyboard shortcuts** — Full cheatsheet with `F1`
- **Branch grouping** — `feature/xxx` branches grouped in folders
- **File tree view** — Toggle between flat and tree layouts
- **Context menus** — Rich right-click menus everywhere (graph, branches, tags, stashes)
- **Toast notifications** — Feedback for every action

## Download

### Latest Release

| Platform | Download |
|----------|----------|
| **macOS** (Apple Silicon) | [GitSquid-1.2.0-mac.dmg](https://github.com/TheMax98000/gitsquid-releases/releases/download/v1.2.0/GitSquid-1.2.0-mac.dmg) |
| **Windows** | [GitSquid-1.2.0-win-setup.exe](https://github.com/TheMax98000/gitsquid-releases/releases/download/v1.2.0/GitSquid-1.2.0-win-setup.exe) |
| **Linux** | [GitSquid-1.2.0-linux.AppImage](https://github.com/TheMax98000/gitsquid-releases/releases/download/v1.2.0/GitSquid-1.2.0-linux.AppImage) |

> Go to [Releases](https://github.com/TheMax98000/gitsquid-releases/releases) for all versions.

## Installation

### macOS
1. Download the `.dmg` file
2. Open it and drag GitSquid to your Applications folder
3. Launch GitSquid from your Applications

### Windows
1. Download the `-setup.exe` file
2. Run the installer
3. Launch GitSquid from the Start menu

### Linux
1. Download the `.AppImage` file
2. Make it executable: `chmod +x GitSquid-*.AppImage`
3. Run it: `./GitSquid-*.AppImage`

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Desktop | Electron |
| Frontend | React 18 + TypeScript |
| State | Zustand |
| Git | simple-git (CLI wrapper) |
| Graph | Canvas 2D (virtual scrolling) |
| Terminal | xterm.js + node-pty |
| Styling | CSS Modules + custom properties |

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Cmd+N` | New branch |
| `Cmd+F` | Search commits |
| `Cmd+Enter` | Commit (in staging) |
| `Cmd+`` ` | Toggle terminal |
| `F1` | Keyboard shortcuts |
| `Escape` | Close / deselect |
| Double-click branch | Checkout |
| Right-click | Context menu |

## Screenshots

### Commit Graph
Interactive graph with avatars, branch coloring, stash nodes, and search.

### Diff Viewer
Unified, split, and blame views with syntax highlighting.

### Integrated Terminal
Full terminal access without leaving the app.

### Settings
Profiles, integrations, keyboard shortcuts, and language selection.

---

<p align="center">
  <strong>GitSquid</strong> &mdash; Git made visual.<br>
  <a href="https://github.com/TheMax98000/gitsquid-releases/releases/latest">Download now</a>
</p>
