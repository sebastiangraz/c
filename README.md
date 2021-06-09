# c
c zsh plugin for lazy gitters like me

Usage

`c 'Commit message'` or no message is just `c`

What it does

`git pull -rebase && git add . && git commit '${message}'`

With extra steps

### Oh-My-Zsh

If you're using [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh), you can do:

1. `git clone git@github.com:sebastiangraz/c.git ~/.oh-my-zsh/custom/plugins/c`
2. `echo "plugins+=(c)" >> ~/.zshrc`

(Alternatively, you can add the `c` plugin to the `plugins=(...)` local in your `~/.zshrc` manually.)

Inspired by https://github.com/robertzk/send.zsh
