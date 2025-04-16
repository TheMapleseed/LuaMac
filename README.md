# Lua 5.4.7 for macOS

This repository contains Lua 5.4.7 compiled specifically for macOS using Clang.

## Features

- Built with Clang compiler on macOS
- Optimized for macOS environments
- Passes all official Lua test suites

## Installation

The Lua interpreter can be installed to your system with:

```bash
sudo cp lua /usr/local/bin/
```

## Building from Source

To rebuild Lua from source:

1. Clone this repository
2. Run `make all`
3. Optionally install with `sudo cp lua /usr/local/bin/`

## Testing

The build has been tested using the official Lua 5.4.7 test suite.

## License

Lua is licensed under the terms of the MIT license. See the LICENSE file for details.
