# Neovim Quick Guide

Neovim is a super cool text editor that lets you do lots of things with just your keyboard! Here's a simple guide to get you started:

## Opening and Closing Neovim

* `nvim`: Opens Neovim.
* `nvim filename`: Opens Neovim and loads the file named "filename".
* `:q`: Closes Neovim (if you haven't made any changes).
* `:wq`: Saves your changes and closes Neovim.
* `:q!`: Closes Neovim without saving changes (use this if you don't want to keep your edits).

## Modes in Neovim

Neovim has different "modes" for different things:

* **Normal Mode:** This is the default mode. You use it for moving around and giving commands.
* **Insert Mode:** This is for typing text. You switch to it by pressing `i`.
* **Visual Mode:** This is for selecting text. You switch to it by pressing `v`.
* **Command-line Mode:** This is for typing commands (like saving or quitting). You switch to it by pressing `:`.

## Moving Around

* `h`: Move left.
* `j`: Move down.
* `k`: Move up.
* `l`: Move right.
* `w`: Move to the start of the next word.
* `b`: Move to the start of the previous word.
* `0` (zero): Move to the start of the line.
* `$`: Move to the end of the line.
* `gg`: Move to the top of the file.
* `G`: Move to the bottom of the file.

## Editing Text

* `i`: Enter Insert Mode at the current cursor position.
* `a`: Enter Insert Mode after the current cursor position.
* `o`: Open a new line below the current line and enter Insert Mode.
* `O`: Open a new line above the current line and enter Insert Mode.
* `dd`: Delete the current line.
* `yy`: Copy (yank) the current line.
* `p`: Paste the copied text after the current cursor position.
* `u`: Undo the last change.
* `Ctrl + r`: Redo the last undone change.

## Selecting Text (Visual Mode)

* `v`: Enter Visual Mode (character-wise selection).
* `V`: Enter Visual Mode (line-wise selection).
* `Ctrl + v`: Enter Visual Block Mode (column-wise selection).
* Use the movement keys (`h`, `j`, `k`, `l`, `w`, `b`, etc.) to select text.
* `y`: Yank (copy) the selected text.
* `d`: Delete the selected text.

## Searching

* `/pattern`: Search for "pattern" (press `Enter` to start the search).
* `n`: Go to the next search result.
* `N`: Go to the previous search result.

## Saving and Exiting

* `:w`: Save the current file.
* `:wq`: Save and close Neovim.
* `:q!`: Close Neovim without saving.

## Tips for Getting Started

* Practice moving around with `h`, `j`, `k`, and `l`. It might feel weird at first, but it's super fast once you get used to it!
* Try editing text in Insert Mode (`i`) and deleting lines (`dd`).
* Experiment with Visual Mode (`v`) to select and copy text.
* Remember `:w` to save your work!
* Neovim is super customizable with plugins and settings. You can make it do almost anything you want later on.
