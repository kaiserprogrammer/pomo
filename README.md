# pomo
CMD-line Pomodoro timer

## Commands
### Start Pomodoro
```bash
pomo 25m task
pomo 1h another-task
```

### List Active Timers
```bash
pomo
```
OUTPUT:
```console
ID  NAME          REMAINING
1   task          00:24:55
2   another-task  00:59:58
```

### Kill Timers
#### All
```bash
pomo k
```

#### Specific
```bash
pomo k 2
```

## Installation

Copy file in your bin folder and make it executable

```bash
chmod a+x pomo
cp pomo /usr/bin/
```

## Dependencies

* notify-send
