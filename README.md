## 安装 nerd 字体

https://link.juejin.cn/?target=https%3A%2F%2Fwww.nerdfonts.com%2Ffont-downloads

下载后，更换 termimal 里的字体即可。

## 需要手动安装的依赖（插件用）

### rigpgrep
```
brew install ripgrep
```

### fd

```
brew install fd
```

### eslint_d

如果发现格式化、lint 检查失效，就装一下

```
yarn global add eslint_d
```

### prettier

如果发现格式化、lint 检查失效，就装一下

```
yarn global add prettier
```

## iterm2 设置

有几个快捷键用到了 opt ，但 neovim 不识别 opt，需要设置 iterm2 将 opt 转换成 meta 才可以正常使用

## treesitter

第一装完插件后，运行会报错，需要手动 :TSUpdate 一次才行，原因未知。
