# Just enough tmux conf
˗ˏˋ ★ ˎˊ˗ The best and greatest tmux.conf ever created by human inteligence :) and made with ❤️ ˗ˏˋ ★ ˎˊ˗ 

Installation
------------

Requirements:

  - tmux **`>= 2.6`** running on Linux, macOS, OpenBSD, Windows (WSL or Cygwin)
  - sed, uptime, whoami
  - Outside of tmux, the `TERM` environment variable must be set to
    `xterm-256color`. To verify it run in your terminal : 
```
echo $TERM
```
Installing in `~`:
```
# enter in your users' home folder
cd
# clone this repository in a .tmux folder
git clone --single-branch https://github.com/synergops/.tmux.git
# create a shortcut of the .tmux.conf in users' home folder
ln -s -f .tmux/.tmux.conf .
```
Bindings
--------

tmux may be controlled from an attached client by using a key combination of a
prefix key, followed by a command key. This configuration is keeping `C-b` as the default prefix. 
In the following list of key bindings:
  - `<prefix>` means you have to hit <kbd>Ctrl</kbd> + <kbd>b</kbd>
  - `<prefix> c` means you have to hit <kbd>Ctrl</kbd> + <kbd>b</kbd> followed by <kbd>c</kbd>
  - `<prefix> C-c` means you have to hit <kbd>Ctrl</kbd> + <kbd>b</kbd> followed by <kbd>Ctrl</kbd> + <kbd>c</kbd>

For more, please read the `.tmux.conf` which is self exlanatory 
