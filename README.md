# Luacheck action

![GitHub](https://img.shields.io/github/license/Jayrgo/luacheck-action?style=flat-square)

## Table of Contents

- [Inputs](#Inputs)
- [Usage](#Usage)
- [License](#License)

## Inputs
- **Optional** `files`: List of files, directories and rockspecs to check.
- **Optional** `config`: Path to configuration file.
- **Optional** `args`: Arguments passed to luacheck. (Look at [Command line options](https://github.com/mpeterv/luacheck/blob/master/docsrc/cli.rst#command-line-options) for all arguments)

## Usage
```yaml
- uses: Jayrgo/luacheck-action@v1
  with:
    # List of files, directories and rockspecs to check.
    # Default: .
    files: '.'

    # Path to configuration file.
    # Default: .luacheckrc
    config: '.luacheckrc'

    # Arguments passed to luacheck.
    # Default: -q
    args: '-q'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
