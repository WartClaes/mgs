# Multi Git Status

based on [https://github.com/fboender/multi-git-status](https://github.com/fboender/multi-git-status)

## Usage

1. Clone the repo to your local image
2. Add the repo folder to your PATH variable

    ```bash
    # .bash_profile
    export PATH="path/to/repo/:$PATH"
    ```
3. Run the scripts
    ```bash
    $ mgs
    ```

## Options

```
$ mgs --help

Usage: mgs

mgs [-h, --help]	Sets a sub directory
mgs -d <directory>	Sets a sub directory
mgs -l <number>		Sets a depth for the search
mgs -s			Silences 'ok' messages
mgs -f			Show changed files
```
