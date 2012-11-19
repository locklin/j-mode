
# J Mode

Provides font-lock and basic REPL integration for the
[J programming language](http://www.jsoftware.com)

## Installation

The only method of installation is to check out the project, add it
to the load path, and load normally. This may change one day.

    ;; Put this in your emacs config
    (add-to-list 'load-path "/path/to/j-mode/")
    (load "j-mode")


## REPL Interaction

Interaction is rudimentary. <kbd>M-x j-console</kbd> or
<kbd>C-c !</kbd> in `j-mode` will start a new jconsole process wrapped in a
comint buffer.

The following commands are provided as convenience methods

- <kbd>C-c C-l</kbd> Executes the current line
- <kbd>C-c C-r</kbd> Executes the current region
- <kbd>C-c C-c</kbd> Executes the current buffer

All of them will start a jconsole session if there isn't one already running.


## License

Copyright (C) 2012 Zachary Elliott

Distributed under the GNU General Public License; see <kbd>C-h t</kbd> in emacs to view.
