This is a plugin for [`YAGS`](https://github.com/pltanton/yags).

# Configuration

Displays current pulse volue, using pulselib.

Available configuration keys:

| Key    | Description            | Default value               |
| ---    | ---                    | ---                         |
| sink   | sink to monitor        | /org/pulseaudio/core1/sink0 |
| high   | format for _vol_ > 66  | {vol}                       |
| medium | format for _vol_ > 33  | {vol}                       |
| low    | format for _vol_ <= 33 | {vol}                       |
| muted  | format for muted sink  | {vol}                       |

Available variables for interpolation:

| Variable name | Description                      |
| ---           | ---                              |
| vol           | current volume level in percents |
