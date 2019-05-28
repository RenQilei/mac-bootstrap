# 前提条件

已经安装了 iTerm2。

# 安装 Oh My Zsh

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

安装完成后，$HOME 目录下就会有一份配置文件：```~/.zshrc```，可视为 ```.bashrc``` 文件使用。

# 安装插件

编辑 ```~/.zshrc``` 文件：
```
plugins=(extract git history-search-multi-word pip zsh-syntax-highlighting z zsh_reload zsh-completions zsh-autosuggestions)
```

其中，

* history-search-multi-word
* zsh-syntax-highlighting
* zsh-completions
* sh-autosuggestions

为第三方插件，可自行选择安装。
