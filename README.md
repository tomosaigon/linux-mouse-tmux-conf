# linux-mouse-tmux-conf

Used on Linux with mouse controls (activating panes, switching windows in the tabs list, selecting text to copy). Copy relies on xclip so this only works locally on Linux (with X11), but mouse otherwise works on remote ssh connections. Different colors of tabs depending on connection. 

Keeps panes around after process exits, so ^x kills the pane.

Works with different versions of tmux.

Uses resurrect/continuum to save state and my own uncommitted script to save pane screen captures.

# Usage:

1. Copy this to ~/.tmux.conf
2. Make sure to run: git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
3. Install plugins below manually by running ^I
