# cast call --create

ignores the address field and simulates creating a contract

```bash
$ cast call --create --help
```

```txt
Usage: cast call --create [OPTIONS] <CODE> [SIG] [ARGS]...

Arguments:
  <CODE>
          Bytecode of contract

  [SIG]
          The signature of the constructor

  [ARGS]...
          The arguments of the constructor

Options:
      --value <VALUE>
          Ether to send in the transaction.
          
          Either specified in wei, or as a string with a unit type.
          
          Examples: 1ether, 10gwei, 0.01ether

  -h, --help
          Print help (see a summary with '-h')

Display options:
      --color <COLOR>
          Log messages coloring

          Possible values:
          - auto:   Intelligently guess whether to use color output (default)
          - always: Force color output
          - never:  Force disable color output

      --json
          Format log messages as JSON

  -q, --quiet
          Do not print log messages

      --verbose
          Use verbose output
```