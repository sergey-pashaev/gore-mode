# gore-mode
Simple comint-based mode for gore (command-line evaluator for golang code)

# dependencies
* `go-mode` (available on MELPA)
* [gore](https://github.com/sriram-srinivasan/gore)

# install
1. Install all dependencies
2. Get gore-mode: `git clone git://github.com/sergey-pashaev/gore-mode.git`
3. Put gore-mode.el in your load path: `(add-to-list 'load-path "/<path to gore-mode dir here>/")`
4. Add `(require 'gore-mode)` to your .emacs
5. Set correct gore binary path: `(setq gore-bin-path "/your/path/to/gore/binary")`
6. `M-x run-gore` to enable gore-mode in *gore* buffer or `M-x gore-mode` to enable gore-mode in current-buffer

# features
* gore-expr-mode : `C-<return>` wraps user input like so: `println(" + %user_input% + ")` then sends it to gore

# screenshot
![screenshot](https://github.com/sergey-pashaev/gore-mode/raw/master/img/scr.png)
