# 使用方法

> 参照: https://packagecontrol.io/docs/syncing

```bash
# download git repository to special directory
$ git clone git@github.com:northup/sublime_config.git ~/Workspace/personal/sublime_config
# replace default config folder(only for Mac OS X) with git repository
$ rm -rf ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
$ ln -sf $HOME/Workspace/personal/sublime_config/User ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
```
