Add to ~/.bashrc:
```
export PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]>\[\033[00m\]:\[\033[01;34m\]\W\[\033[33m\]$(__git_ps1)\[\033[00m\]\$ '
```
