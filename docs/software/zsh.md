# zsh

## oh-my-zsh

用于自定义 zsh 的配置

1. 主题配置
2. 插件安装

安装

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

[Github](https://github.com/ohmyzsh/ohmyzsh)
[zsh 插件](zsh)

## zsh 插件

### autojump

用于常用目录间的快速跳转(通过维护命令行中最常用的目录的数据库来工作)

安装

```sh
# 推荐
brew install autojump

# OR
git clone git://github.com/joelthelion/autojump.git

cd autojump

./install.py or ./uninstall.py
```

[Github](https://github.com/wting/autojump)

### z

和 `autojump` 功能一致，是 `oh-my-zsh` 内置插件

[Github](https://github.com/rupa/z)

### zsh-syntax-highlighting

终端语法高亮显示

安装

```sh
# clone
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# 在 ~/.zshrc 中配置(在 plugins 的最后面加上 zsh-syntax-highlighting )
plugins=(其他插件 zsh-syntax-highlighting)

# 使配置生效
source ~/.zshrc
```

[Github](https://github.com/zsh-users/zsh-syntax-highlighting)

### zsh-autosuggestions

根据您的历史记录和完成情况建议您键入的命令

安装

```sh
# clone
git clone git://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions

# 在 ~/.zshrc 中配置
plugins=(其他插件 zsh-syntax-highlighting)

# 使配置生效
source ~/.zshrc
```

[Github](https://github.com/zsh-users/zsh-autosuggestions)
