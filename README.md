# Vim Cheatsheet for Git Merges

Vim operates in various modes, the most common being Normal mode and Insert mode. When Git launches Vim (e.g., for commit messages), it starts in Normal mode.

## Basic Navigation

- **`i`**: Enter Insert mode (to start typing/editing)
- **`Esc`**: Return to Normal mode (to use commands)
- **`h`**, **`j`**, **`k`**, **`l`**: Move left, down, up, right (in Normal mode)

## Editing

- **Insert mode**: Type normally as in other editors. To return to Normal mode, press `Esc`.
- **`u`**: Undo last change (in Normal mode)
- **`Ctrl` + `r`**: Redo (in Normal mode)

## Saving and Exiting

- **`:w`**: Write (save) the file (in Normal mode)
- **`:q`**: Quit Vim (in Normal mode)
  - If Vim complains about unsaved changes, use `:q!` to force quit without saving.
- **`:wq`** or **`ZZ`**: Save and quit (in Normal mode)

## Git Merge Specific

- **Edit Merge Message**: Enter Insert mode (`i`), edit the message, then return to Normal mode (`Esc`).
- **Save Merge Message**: `:wq` to save and exit, finalizing the merge commit.

## Extra Tips

- **`:help`**: Show Vim help (in Normal mode)
- **`:set number`**: Show line numbers (useful for large commit messages)

Remember, to switch between modes: `i` for insert, `Esc` for normal.
