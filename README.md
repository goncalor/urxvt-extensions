A few rxvt-unicode extension scripts.

clipboard-shortcuts
-------------------

This extesion allows you to configure shortcuts to copy to and paste from the clipboard.

#### Usage

- Add the script to the directory `~/.urxvt/ext/`
- Add the following lines to your `~/.Xresources` or `~/.Xdefaults`:

      URxvt*keysym.Control-Shift-C: clipboard-shortcuts:copy
      URxvt*keysym.Control-Shift-V: clipboard-shortcuts:paste

This configuration would allow you to use `ctrl-shift-c` to copy the selected text to the clipboard and `ctrl-shift-v` to paste.
This is the same configuration used in GNOME Terminal.
