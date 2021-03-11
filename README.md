# alfred-workflows
Some alfred Workflows that I like

## Journal - Manage a text-based line journal
  - Variables:
    - `journalpath` - Path to a folder to store journals in. The workflow will create a new file every day that you use this. Defaults to a Google Drive folder.
    - `extension` - The extension for the files. Defaults to `.md`. Include the period before the extension
  - Keywords: 
    - `jl {query}` - Adds `{query}` to today's journal, creating today's journal if it doesn't exist (will be at `{var:journalpath}/{date:YYYY-mm-dd}{var:extension}`).
    - `jl` - Opens VSCode to your `journalpath`, focusing on today's journal entry, creating it if it doesn't exist
    - `yjl` - Opens Yesterday's journal in VSCode. Will send a notification if the file doesn't exist.
  - Hotkeys:
    - `Cmd-Shift-J` - Same as `jl`
    - `Cmd-Alt-Shift-J` - Same as `yjl`

## Copy Shrug - ¯\\\_(ツ)_/¯ at your fingertips
  - Keywords:
    - `shrug` - Copies `¯\_(ツ)_/¯` to your clipboard

## Repl Shortcuts - Quick links to some REPLs at repl.it
  - Keywords:
    - `repl` - Opens a list of options to open:
      - PHP - Opens a PHP CLI repl
      - PHP Web - Opens a PHP Web Server repl
      - Javascript - Opens a Node.js repl
    
