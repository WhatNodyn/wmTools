# Autolocker
It watches for Lock signals for the current session on D-Bus and reacts accordingly,
by locking your session and optionally switching to the greeter.

# How to Use It
It's mainly meant to be used with i3, so to use it, just start `autolock` with your session,
passing the lockscreen's command as an argument.

Then replace all keybindings and commands that you used to lock with ones to the script named `lock`,
which will lock your screen through logind, thus ensuring `autolock` is managing your lockscreen and
won't try to start another one over it, or anything weird.
