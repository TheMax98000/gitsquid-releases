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
  <img src="https://raw.githubusercontent.com/TheMax98000/gitsquid-releases/main/screenshot.png" alt="GitSquid — Commit Graph" width="900">
</p>

## Features

### Core Git
- **Interactive commit graph** — Canvas-based with virtual scrolling, Gravatar avatars, branch coloring
- **Full git workflow** — Stage, unstage, commit (with amend), push, pull, fetch
- **Partial staging** — Stage/unstage individual hunks from the diff view
- **Drag & drop staging** — Drag files and folders between unstaged/staged
- **Branch management** — Create, delete, rename, checkout, merge, rebase
- **Diff viewer** — Unified, split, full file, and blame views with syntax highlighting
- **Git blame** — Inline blame with author, date, and click-to-select commit
- **Stash management** — Save, apply, pop, drop, visible on the graph
- **Tags** — Create, delete, push to remote
- **Cherry-pick, revert, reset** — Full context menu on commits
- **Conflict resolution** — Accept ours/theirs per file, 3-tab diff view
- **Auto-stash on checkout** — Automatically stash and reapply changes
- **GPG signing** — Sign commits/tags, verified badge on graph and detail
- **Worktrees** — Create, remove, lock/unlock, open in new tab
- **Reflog viewer** — Complete action history with color-coded badges
- **Git LFS** — Track patterns, pull/push LFS objects, status panel
- **Submodules** — List, init, update, open in new tab
- **Gitflow** — Init, feature/release/hotfix start & finish

### Integrations
- **GitHub, GitLab, BitBucket** — Connect via Personal Access Token
- **Pull Requests** — List, create, review (approve, request changes, comment)
- **Issues** — List, create, close, view detail
- **Clone from provider** — Browse and search your remote repositories
- **Create remote repos** — Initialize and push to GitHub/GitLab/BitBucket

### Productivity
- **Multi-repo tabs** — Open multiple repositories, persisted across restarts
- **Integrated terminal** — Full terminal (xterm.js + node-pty) with `Cmd+``
- **Profiles** — Switch between different Git identities and provider accounts
- **Graph search** — Filter commits by message, author, or hash (`Cmd+F`)
- **Commit templates** — Conventional commits (feat, fix, docs, etc.) one-click prefill
- **Repository statistics** — Authors table, commit counts, GitHub-style activity heatmap
- **Auto-updater** — Check for updates from Settings

### UI & UX
- **Dark & Light themes** — Toggle in Settings > Appearance
- **10 languages** — English, French, Spanish, German, Portuguese, Italian, Japanese, Chinese, Korean, Russian
- **Keyboard shortcuts** — Full cheatsheet with `F1`
- **Branch grouping** — `feature/xxx` branches grouped in folders
- **File tree view** — Toggle between flat and tree layouts
- **Context menus** — Rich right-click menus on files, commits, branches, tags, stashes, folders
- **Toast notifications** — Feedback for every action

## Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/TheMax98000/gitsquid-releases/main/screenshot2.png" alt="GitSquid — Diff View" width="900">
</p>
<p align="center"><em>Diff viewer with unified/split/blame modes and partial staging</em></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/TheMax98000/gitsquid-releases/main/screenshot3.png" alt="GitSquid — Light Theme" width="900">
</p>
<p align="center"><em>Light theme</em></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/TheMax98000/gitsquid-releases/main/screenshot4.png" alt="GitSquid — Settings" width="900">
</p>
<p align="center"><em>Settings — Profiles, Integrations, Appearance, Language</em></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/TheMax98000/gitsquid-releases/main/screenshot5.png" alt="GitSquid — Statistics" width="900">
</p>
<p align="center"><em>Repository statistics with activity heatmap</em></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/TheMax98000/gitsquid-releases/main/screenshot6.png" alt="GitSquid — Terminal" width="900">
</p>
<p align="center"><em>Integrated terminal</em></p>

## Download

### Latest Release

| Platform | Download |
|----------|----------|
| **macOS** (Apple Silicon) | [GitSquid-1.3.0-mac.dmg](https://github.com/TheMax98000/gitsquid-releases/releases/download/v1.3.0/GitSquid-1.3.0-mac.dmg) |
| **Windows** | [GitSquid-1.3.0-win-setup.exe](https://github.com/TheMax98000/gitsquid-releases/releases/download/v1.3.0/GitSquid-1.3.0-win-setup.exe) |
| **Linux** | [GitSquid-1.3.0-linux.AppImage](https://github.com/TheMax98000/gitsquid-releases/releases/download/v1.3.0/GitSquid-1.3.0-linux.AppImage) |

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
| Drag file | Stage/unstage |

---

<p align="center">
  <strong>GitSquid</strong> &mdash; Git made visual.<br>
  <a href="https://github.com/TheMax98000/gitsquid-releases/releases/latest">Download now</a>
</p>
