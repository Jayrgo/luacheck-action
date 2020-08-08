# Luacheck action

## Inputs
- **Optional** `files`: List of files, directories and rockspecs to check.
- **Optional** `config`: Path to configuration file.
- **Optional** `arguments`: Arguments passed to luacheck.

## Usage
```yaml
- uses: Jayrgo/luacheck-action@0.1.0
  with:
    # List of files, directories and rockspecs to check.
    # Default: .
    files: '.'

    # Path to configuration file.
    # Default: .luacheckrc
    config: '.luacheckrc'

    # Arguments passed to luacheck.
    # Default: -q
    arguments: '-q'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
