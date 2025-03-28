# Tmux Quick Guide

Tmux is like a super-powered terminal that lets you split your screen and keep programs running even after you close your terminal window. Here's a simple guide to get you started:

## Starting and Stopping Tmux

* `tmux`: Starts a new Tmux session. Think of a session as a workspace.
* `tmux new -s myproject`: Starts a new session named "myproject". Naming your sessions helps you keep them organized!
* `tmux attach`: Joins the last Tmux session you were using.
* `tmux attach -t myproject`: Joins the session named "myproject".
* `tmux ls`: Shows you a list of all your running Tmux sessions.
* `tmux kill-session -t myproject`: Stops the session named "myproject".

## Using the Prefix Key

* Most Tmux commands start with a special key combination called the "prefix" key. By default, it's `Ctrl + b`. So, when you see `prefix + something`, it means press `Ctrl + b`, let go, and then press the "something" key.

## Working with Windows

* `prefix + c`: Creates a new window inside your Tmux session. Windows are like tabs in a web browser.
* `prefix + ,`: Lets you rename the current window. This helps you remember what's running in each window.
* `prefix + w`: Shows a list of all your windows in the current session.
* `prefix + n`: Moves to the next window.
* `prefix + p`: Moves to the previous window.
* `prefix + 1` (replace 1 with any number): Jumps to the window with that number.
* `prefix + &`: Closes the current window.

## Working with Panes (Splitting the Screen)

* `prefix + %`: Splits the current window into two vertical panes.
* `prefix + "`: Splits the current window into two horizontal panes.
* `prefix + o`: Moves to the next pane.
* `prefix + {`: Moves the current pane to the left.
* `prefix + }`: Moves the current pane to the right.
* `prefix + <arrow key>`: Moves to the pane in the direction of the arrow.
* `prefix + x`: Closes the current pane.
* `prefix + z`: Makes the current pane full-screen (zoom) and then returns it to its original size.
* `prefix + <space>`: Changes the layout of your panes.

## Copying and Pasting

* `prefix + [`: Enters copy mode, which lets you scroll and copy text.
    * In copy mode:
        * Use the arrow keys or `Page Up`/`Page Down` to scroll.
        * Press `Space` to start selecting text.
        * Press `Enter` to copy the selected text.
        * Press `q` to exit copy mode.
* `prefix + ]`: Pastes the text you copied.

## Leaving and Returning to Tmux

* `prefix + d`: Detaches from your current Tmux session. This means the session keeps running in the background, even if you close your terminal.
* `tmux attach -t myproject`: Reconnects to the session named "myproject".

## Tips for Getting Started

* Start by practicing the basic commands: `tmux`, `prefix + c`, `prefix + %`, `prefix + "`, `prefix + d`, and `tmux attach`.
* Get used to using the prefix key. It might feel a little weird at first, but you'll get the hang of it!
* Give your windows and sessions names to stay organized.
* Tmux is very customizable, you can change the prefix key and many other things later on.
