# 简单的 node 代理服务
### 指令
- `npm i -g proxy-serve`
  - `proxy` 启动服务，默认端口`19527`
  - `proxy 9527` 启动服务，端口`9527`


- `npm init proxy-serve`服务器执行此命令即可
  - 默认端口：`19527`
  - 自定义端口启动：`npm init proxy-serve 9527`，确保端口没被占用，否则报错


- 通过`git`安装
  - `git clone https://github.com/code-ba/proxy-serve.git`
  - `cd proxy-serve`
  - 启动指令：`npm start`、`npm run server`（固定默认端口：`19527`）
  - 自定义端口：`node bin/index.js 9527`

---

### 配置
- 使用`ip:port`即可链接
  - 浏览器插件：[SwitchyOmega](https://proxy-switchyomega.com)（支持`chrome`、`firefox`）
  - 协议走`socket`、不用设置账号密码
  - 配置好后，在插件选择你配置的情景模式，然后打开百度，输入`ip`即可查看当前的地址

---

### 打赏

您的支持是我持续更新的动力！

<img src="https://cdn.jsdelivr.net/gh/cxvh/static@main/img/20210218193037.png" width="200" height="200" alt="微信">
<img src="https://cdn.jsdelivr.net/gh/cxvh/static@main/img/20210218192738.jpg" width="200" height="200" alt="支付宝">

---