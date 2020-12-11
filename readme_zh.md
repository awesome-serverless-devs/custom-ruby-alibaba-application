# 阿里云函数计算 Lua 案例

只需几步就可以快速在阿里云函数计算服务上体验 Lua ：

- 初始化项目：`s init custom-typescript -p alibaba`
- 进入项目：`cd custom-typescript`
- 安装依赖：`s install docker -f ./fcfile`
- 部署项目：`s deploy`
- 触发项目：`s invoke remote -e "HelloWorld"`

即可实现`Lua`案例的初始化、部署整个流程。