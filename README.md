# bash-git-pretty

1. ~/git-prompt.sh
https://raw.githubusercontent.com/git/git/master/contrib/completion/git-prompt.sh  

2. ~/git-completion.bash
https://raw.githubusercontent.com/git/git/master/contrib/completion/git-completion.bash

3. ~/.bashrc.sh


source ~/git-completion.bash

green="\[\033[0;32m\]"

blue="\[\033[0;34m\]"

purple="\[\033[0;35m\]"

reset="\[\033[0m\]"

source ~/git-prompt.sh

export GIT_PS1_SHOWDIRTYSTATE=1

export PS1="$purple\u$green\$(__git_ps1)$blue \W $ $reset"

                                                          
