# claunch

A small CLI tool that helps launch Claude Code from a remembered list of directories. When run, it shows an interactive picker with your current directory and previously visited locations, lets you select one, and launches `claude` in it.

## Installation

```
pip install ailaunch
```

## Usage

```
claunch [-- <claude args>]
```
How can you pass cli arguments to claude when you launch it through claunch?
Anything after `--` is forwarded directly to the `claude` process.

## Picker controls

| Key | Action |
|-----|--------|
| Up / Down | Navigate the list |
| Enter | Launch Claude in the selected directory |
| c | Launch Claude in the current directory immediately |
| 1-9 | Jump to and launch a numbered entry |
| d | Delete the selected entry from history |
| Home / End | Jump to first or last entry |
| q / Esc | Quit without launching |
