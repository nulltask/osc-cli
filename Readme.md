
# osc-cli

osc command-line interface

## Installation

    $ npm install -g osc-cli

## Usage

### Send

    $ osc /foo bar baz  # => send /foo with bar and baz to localhost:7400

with host

    $ osc --host 192.168.0.10:9337 /baz 1 2 3

### Listen

    $ osc-listen -a /address/whatever -p 12345

## License

MIT
