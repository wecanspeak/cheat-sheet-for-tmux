Cheat sheet for tmux
--------------------

  For my little brains.

### Out session (@ original shell)

| action | command |
| ------ | ------- |
| create session | `tmux new -s [session-name]` |
| kill session | `tmux kill-session -t [session-name]` |
| attach session | `tmux attach -t [session-name]` |
| rename session | `tmux rename-session -t [old-name] [new-name]` |
| list session | `tmux ls` |

### In session 

| action | command |
| ------ | ------- |
| create window | `^b + c` |
| rename window | `^b + ,` |
| navigate window | `^b + n` `^b + p` `^b + l`|
| detach session | `^b + d` |
| help | `^b + ?` |

### In window / pane

| action | command |
| ------ | ------- |
| split pane | `^b + %`  `^b + "` |
| delete pane | `^b + x`  `^d` (no warning) |
| select pane | `^b + arrow_key` |
| resize pane | `^b + <M-arrow_key>` |

