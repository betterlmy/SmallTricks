# homebrew

## brew 安装脚本（手动选择软件源）

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## brew 卸载脚本

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/uninstall.sh)"
```

## 常用命令

安装软件：`brew install xxx`
卸载软件：`brew uninstall xxx`
搜索软件：`brew search xxx`
更新软件：`brew upgrade xxx`
查看列表：`brew list`
更新brew：`brew update`
清理所有包的旧版本：`brew cleanup`
清理指定包的旧版本：`brew cleanup $FORMULA`
查看可清理的旧版本包，不执行实际操作：`brew cleanup -n`
