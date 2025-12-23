打开VPS官网，点击“开始使用”或“注册账号”。

填写用户名、电子邮箱（推荐Gmail）并设置密码，点击创建账户。

前往你的邮箱，找到激活邮件并点击链接完成激活。

登录官网后，找到“添加服务器”或“创建服务器”。

配置服务器：

名称： 随意填写（例如：001）

节点选择： 建议选择“节点6（美国）”

创建服务器软件选择：

node.js generic
修改启动选项（Startup）变量参数

bash
一键安装脚本

curl -Ls https://raw.githubusercontent.com/eishare/tuic-hy2-node.js-python/main/hy2.sh | sed 's/\r$//' | bash -s -- 替换为你的端口# 1.Hysteria2在Nodejs/Python一键脚本极简部署（Pterodactyl 翼龙面板）

* 更新自适应端口，无需再手动设置

* Hysteria2版本：2.6.5 官方更新说明（原文直译）：

  修复了随着每个客户端连接而累积的服务器端内存泄漏问题

```
curl -Ls https://raw.githubusercontent.com/eishare/tuic-hy2-node.js-python/main/hy2.sh | sed 's/\r$//' | bash
```


---------------------------------------

# 2.TUIC在Nodejs/Python一键脚本极简部署（Pterodactyl 翼龙面板）

* 自适应端口，无需再手动设置

* TUIC版本：1.4.5 官方更新说明（原文直译）：

  🐛 错误修复
     （服务器）发送 FIN 以作废stream reset by peer

   ⚙️ 杂项任务
      将日志更改为跟踪

```
curl -Ls https://raw.githubusercontent.com/eishare/tuic-hy2-node.js-python/main/tuic.sh | sed 's/\r$//' | bash
```

