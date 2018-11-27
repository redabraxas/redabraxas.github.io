---
title: "tmux(terminal multiplexer) 사용법"
output: true
sidebar:
  nav: "development"
last_modified_at: 2018-10-04T20:15:56-04:00
toc: true
tags:
  - tool
excerpt: "How to use tmux"
---

### Install
```bash
# Linux
$ sudo apt-get install tmux
# OSX
$ brew install tmux
```

### How to use
```bash
# Open new session
$ tmux new -s [session_name]
# Access session
$ tmux attach -t [session_name]
# List session
$ tmux ls
```
- `Ctrl-b %`: Split vertical
- `Ctrl-b "`: Split horizontal
- `Ctrl-b 방향키`: Move pan
- `Ctrl-b [`: Scroll
- `Ctrl-b d`: Exit