---
title: GNOME  Keybindings
description: Set GNOME Keybindings
tags:
  - GNOME
  - Keybindings
time: '2022-07-08'
---

# gnome-keybindings

Set GNOME Keybindings

## Set `switch-input-source` to `Alt+Shift` open terminal and run:

* Set `switch-input-source` switch to Shift+Alt LEFT

```bash
gsettings set org.gnome.desktop.wm.keybindings switch-input-source "['<Shift>Alt_L']"
```

* set `switch-input-source-backward` to Alt+Shift LEFT

```bash
gsettings set org.gnome.desktop.wm.keybindings switch-input-source-backward "['<Alt>Shift_L']"
```

to view current keybindings run:

```bash
gsettings get org.gnome.desktop.wm.keybindings switch-input-source
gsettings get org.gnome.desktop.wm.keybindings switch-input-source-backward
```
