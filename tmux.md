### Tmux
Master the Tmux terminal multiplexor with the plugings, shortcuts and tips.

##### The status line

https://man7.org/linux/man-pages/man1/tmux.1.html#STATUS_LINE

https://superuser.com/questions/1056977/uppercase-m-at-the-right-of-window-name-in-tmux

##### Attach to different windows in session | Useful for multiple screens for the same session
`$ tmux new-session -t 'original session name or number'`

https://unix.stackexchange.com/questions/24274/attach-to-different-windows-in-session

##### Move a tmux pane from one window to another
`:join-pane -t <int>, where <int> is the index of the window you want to move it into. You can optionally specify -h or -v`

https://bezhermoso.github.io/til/move-a-tmux-pane-from-one-window-to-another/

