# pomo
CMD-line Pomodoro timer

## Start Pomodoro
```bash
pomo 25m task
pomo 1h another-task
```

## List Active Timers
```bash
pomo l
```
OUTPUT:
```console
ID  NAME          REMAINING
1   task          00:24:55
2   another-task  00:59:58
```

## Kill Timers
```bash
pomo k 2
```
