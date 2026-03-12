# CS2_ExecAfter  
  
A plugin (admin-free version) for CS2 built on CounterStrikeSharp that allows you to schedule commands to run on server events or with a delay.

## Requirements

In order for the plugin to work, you must have [CounterStrikeSharp](https://docs.cssharp.dev/guides/getting-started/) installed.

## Installation

1) Download the latest release and open the zip file.
2) Extract the `addons` folder into your server's `game/csgo/` directory
3) Restart your server

## Commands

### exec_after

List commands for the plugin.

### exec_after_map_start

Executes a command after every map start.

`exec_after_map_start "<command>"` where `command` is a string i.e. `exec_after_map_start "exec surf_settings.cfg"`.

### exec_after_map_start_once

Executes a command after the next map start. This will only happen once and not on the subsequent map start.

`exec_after_map_start_once "<command>"` where `command` is a string i.e. `exec_after_map_start_once "exec surf_settings.cfg"`.

### exec_after_map_end

Executes a command every time the map ends.

`exec_after_map_end "<command>"` where `command` is a string i.e. `exec_after_map_end "exec surf_settings.cfg"`.

### exec_after_map_end_once

Executes a command when the map ends. This will only happen once and not on the subsequent map end.

`exec_after_map_end_once "<command>"` where `command` is a string i.e. `exec_after_map_end_once "exec surf_settings.cfg"`.

### exec_after_round_start

Executes a command after every round start.

`exec_after_round_start "<command>"` where `command` is a string i.e. `exec_after_round_start "exec surf_settings.cfg"`.

### exec_after_round_start_once

Executes a command the next time the round starts. This will only happen once and not on the subsequent round start.

`exec_after_round_start_once "<command>"` where `command` is a string i.e. `exec_after_round_start_once "exec surf_settings.cfg"`.

### exec_after_delay

`exec_after_delay <delay> "<command>"` where `delay` is a positive `int` or `float` and `command` is a string i.e. `exec_after_delay 10.5 "say Hello from the past!"`.
  

| Command                       | Parameter               | Description                                      |
|-------------------------------|-------------------------|--------------------------------------------------|
| `exec_after`                  |                         | List commands for the plugin                     |
| `exec_after_map_start`        | `"<command>"`           | Executes a command after every map start         |
| `exec_after_map_start_once`   | `"<command>"`           | Executes a command after the next map start      |
| `exec_after_map_end`          | `"<command>"`           | Executes a command every time the map ends       |
| `exec_after_map_end_once`     | `"<command>"`           | Executes a command when the map ends             |
| `exec_after_round_start`      | `"<command>"`           | Executes a command after every round start       |
| `exec_after_round_start_once` | `"<command>"`           | Executes a command after the next round start    |
| `exec_after_delay`            | `<delay>` `"<command>"` | Execute a command after a delay   |


## License

Distributed under the GPL-3.0 License. See `LICENSE.txt` for more information.
