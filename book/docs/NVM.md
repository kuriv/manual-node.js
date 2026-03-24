# NVM

NVM 是用来管理 Node.js 版本的工具，在 Node.js 官方网站上有适用于 Linux 和 MacOS 的 [安装步骤](https://nodejs.org/zh-cn/download) ，也可以访问 [GitHub](https://github.com/coreybutler/nvm-windows) 获取适用于 Windows 的安装包。安装完成后，执行下面的命令，查看 NVM 的版本。

```
nvm -v
```

执行下面的命令，查看已安装的 Node.js 版本。

```
nvm list
```

执行下面的命令，查看所有可以安装的 Node.js 版本。

```
nvm list available
```

执行下面的命令，安装指定版本的 Node.js 。

```
nvm install 24
```

执行下面的命令，删除指定版本的 Node.js 。

```
nvm uninstall 24
```

执行下面的命令，查看当前使用的 Node.js 版本。

```
nvm current
```

执行下面的命令，切换到指定版本的 Node.js 。

```
nvm use 24
```

