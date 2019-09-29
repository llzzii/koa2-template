## 一个 koa2 + typescript +mysql 的 初始模板

.vscode 文件夹中是 vscode 的 debugger 配置，暂时没搞定热更新 ，后续补上

src 是主要工作目录，执行 tsc 命令时，会生成 dist 文件夹存放编译好的 js 文件

bin 文件为主要配置文件，在 config.ts 中配置端口号及数据库。

controller 文件夹 存放 主要后台执行方法

entity 存放 主要实体字段

middleware 存放中间件 公共方法

model 存放与数据库交互代码

routes 存放与前端交互的路由
