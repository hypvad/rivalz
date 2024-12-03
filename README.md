# rivalz

1.安装

```bash
npm i -g rivalz-node-cli
```

2.运行

```bash
rivalz run
```

- 出现错误，升级node版本
    - **安装 `nvm`：**
        
        如果你还没有安装 `nvm`，可以运行以下命令来安装：
        
        ```bash
        curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
        source ~/.bashrc
        ```
        
    - **安装最新的 Node.js 版本：**
        
        运行以下命令安装最新的稳定版本的 Node.js：
        
        ```bash
        nvm install node
        ```
        
    - **切换到新版本：**
        
        使用以下命令切换到安装的 Node.js 版本：
        
        ```bash
        nvm use node
        ```
        
    - **检查 Node.js 版本：**
        
        再次运行以下命令确认已经安装了更新的 Node.js 版本：
        
        ```bash
        node -v
        ```
        

3.命令

```bash
run -Run the Rivalz rClient CLl
change-hardware-config -Update the rClient CLl configuration
change-wallet -Change the wallet address of the rClient CLl
update-version -Update the rClient CLl version
info - Show the rClient CLl version
report-error -Report the error logs
clear-log -Clears the log files of the rClient CLl
help [command]-Display additional info for a specific command
```
