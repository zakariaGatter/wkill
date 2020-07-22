# Wkill

## Table of Contents

- [About](#about)
- [Quick Start](#quick-start)
- [Why Wkill](#why_wkill)
- [Using Wkill](#using_wkill)


## About

[Wkill] Window Killer-shot

[Wkill] allows you to ...

* kill all windows in all workspaces
* kill all windows in current workspace
* kill all windows in giving workspace
* Select the window you want to kill
* Allows you to change the Select application with VARIABLE

## Quick Start

1. Introduction:

    Installation requires:
    * [Wmctrl]() to get windows and workspaces informations
    * [Dmenu]() Optional for Select option

2. Set up [Wkill]:

    ```bash
    git clone https://github.com/zakariagatter/wkill.git ~/wkill
    mkdir -p ~/.local/bin
    cp ~/wkill/bin/wkill ~/.local/bin
    chmod +x ~/.local/bin/wkill
    ```

## Why Wkill

[Wkill] multi action and tools in one place make you time on any window manager or desktop environment easier and more fun

## Using Wkill

```
WKILL window killer shot
Usage: wkill [OPTIONS] [WORKSPACE]

OPTIONS:
    -a      : Kill all windows in all workspaces
    -c      : Kill all windows in current workspace
    -w <WK> : Kill all windows in workspace (ACCEPT WORKSPACE NAME OR NUMBER)
    -s	    : Select the window you want to kill
    -h      : Show this helo dialog

VARIABLES:
    WKILL_SELECT
        Command for (-s) Select option. default [dmenu -p "Select:"]

NOTE:
    Export WKILL Variables before using them
```

[Wkill]:https://github.com/zakariagatter/wkill
