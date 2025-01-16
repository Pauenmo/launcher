# launcher

Utility to fuzzy find a directory and start tmux and neovim in it.

Usage: launcher [\<path\>]

If the path is provided, launcher will start a new tmux session on that path, named after the path, and open neovim in it. If there is already a tmux session with that name, launcher will attach to it instead of creating a new session.

If the path is not provided, the user can fuzzy find the directory instead.

## Configuration

By default, launcher fuzzy finds directories inside the user's home folder. To change this, create a file ~/.launcher.conf and write "SEARCH_PATH=\<path_to_search_from\>" inside.

## Installation



