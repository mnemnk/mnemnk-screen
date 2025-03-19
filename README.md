# mnemnk-screen

`mnemnk-screen` is a [Mnemnk](https://github.com/mnemnk/mnemnk-app/) agent, which captures screen.

## Installation

1. Create a directory named `mnemnk-screen` under `${mnemnk_dir}/agents/`. `${mnemnk_dir}` is the directory specified in the Mnemnk App settings, and the `agents` directory should already be automatically created.
2. Download the binary from the release page and place it under the newly created `mnemnk-screen` directory. When doing so, remove the suffix like `-v0.4.0-macos-arm64` or `-v0.4.0-win-amd64` from the file name, and rename it to `mnemnk-screen` for mac or `mnemnk-screen.exe` for Windows.
3. Download `mnemnk.json`, and place it in the same `mnemnk-screen` directory.

After installation, restart Mnemnk and `Screen` should be appear in Agents page.

## License

MIT
