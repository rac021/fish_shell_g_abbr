# fish_shell_g_abbr

# Installation

Put `g_abbr.fish` into `~/.config/fish/conf.d/g_abbr.fish`

# How to use it?


## Exp `docker ps -aq` command 

```
  globabbr dkp ' docker ps -a '
```

## You want just type `G<space> `and get `| grep` anywhere then define

```
  globabbr  G   '| grep'
```

Now you easily may type:   `ls -l G<space>` and get `ls -l | grep` 

