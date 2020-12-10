# 阿里云函数计算：custom-ruby

通过该应用，您可以简单快速地在阿里云函数计算创建一个 custom-ruby 服务。

- 下载命令行工具：`npm install -g @serverless-devs/s`

- 配置账号信息，以阿里云为例。
    1. 获取账号Id： https://account.console.aliyun.com/#/secure
        ![](https://images.serverlessfans.com/s-tool/zh/start-1.jpg)
    2. 获取密钥信息：https://ram.console.aliyun.com/manage/ak
        ![](https://images.serverlessfans.com/s-tool/zh/start-2.jpg)
    3. 通过`s config add`进行项目配置
        ![](https://images.serverlessfans.com/s-tool/zh/start-3.jpg)

- 初始化一个模版项目：`s init custom-ruby -p alibaba`
- 进入项目：`cd custom-ruby`

- 执行：`s deploy`即可进行部署。

- 调用: `s invoke remote -e "helloworld"` 即可进行远端调用。

- 至此，我们完成了简单的函数部署功能。