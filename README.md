# mnemnk-screen

`mnemnk-screen` is a [Mnemnk](https://github.com/mnemnk/mnemnk-app/) agent, which captures screen.

## Installation

```shell
cargo install mnemnk-screen
```

## Setup

`mnemnk-screen` is enabled by default. After installation, restart Mnemnk and it should be running.

If it is not enabled, please edit Settings in Mnemnk as follows

```json
  "agents": {
    "screen": {
      "enabled": true
    },
```

Save the settings and restart Mnemnk.

## Development

```shell
> cargo run
...
```

## License

MIT
