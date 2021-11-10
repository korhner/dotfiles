# dotfiles
Store unix dotfiles in git
Source: https://www.atlassian.com/git/tutorials/dotfiles

# Run the following commands to prepare everything:
`git clone --bare <git-repo-url> $HOME/.cfg`
`alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'`
`config checkout`
