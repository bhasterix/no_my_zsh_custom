# no_my_zsh_custom
Repo for easily maintaining my ZSH config across many systems.

# To install:
1. Install ZSH 
2. git clone git@github.com:bhasterix/no_my_zsh_custom.git ./.oh-my-zsh/custom
3. Update ZSH theme to "bhasterix" in ~/.zshrc:
```
ZSH_THEME="bhasterix"
```

## Changes so far:
1. added my theme, so ~/.zshrc file can point at bhasterix theme:
```
ZSH_THEME="bhasterix"
```

2. Added common-aliases for things that will apply on all systems
3. Added common config to autoload and *.zshrc files from a ~/.zshrc.d directory
    - for aliases that I only want in certain places.


# TODO:
1. Add update command to itself to pull down latest version from Github


