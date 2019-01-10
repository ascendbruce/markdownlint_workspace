# Markdownlint workspace

## Why

Couldn't find a good solution for markdown lint need. Decided to maintain my own mdl dotfile.

## Usage

### With VS Code

Rules defined in `.markdownlint.yml`.

1. Install `markdownlint` VS Code extension
2. Edit `working_copy.md` (create one if not exist yet) with VS Code

### With `mdl` command line tool

Rules defined in `markdown.style.rb`.

1. Create or update the content of `working_copy.md`
2. Run

    ```sh
    mdl working_copy.md -c .mdlrc
    ```
