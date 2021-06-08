# g
g zsh plugin for lazy gitters like me

Usage

`g 'Commit message'` or no message is just `g`

What it does

`git pull -rebase && git add . && git commit '${message}'`

With extra steps

### Oh-My-Zsh

If you're using [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh), you can do:

1. `git clone git@github.com:sebastiangraz/g.git ~/.oh-my-zsh/custom/plugins/g`
2. `echo "plugins+=(g)" >> ~/.zshrc`

(Alternatively, you can add the `g` plugin to the `plugins=(...)` local in your `~/.zshrc` manually.)

Inspired by https://github.com/robertzk/send.zsh
