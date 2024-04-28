(1）进入XShell
(2）点左上角文件
(3）点新建
(4）名称随意，协议SSH，主机你的服务器IP（外网IP），端口默认22不变（映射端口和自设端口除外）
(5）确定
(6）在左侧会话管理器，选中设置的配置双击打开
(7）提示输入账号和密码，输入后记得点保存(没有提示可能IP被墙) {账号密码在服务器邮件}

输入以下命令一键安装，回车执行（shift+insert可粘贴）
bash <(curl -s -L https://git.io/v2ray-setup.sh)

自定义安装：
bash <(curl -s -L https://git.io/v2rayinstall.sh)


Network(传输协议)： kcp
type(伪装类型)：dtls

相关命令：

v2ray info 查看 V2Ray 配置信息
v2ray config 修改 V2Ray 配置
v2ray link 生成 V2Ray 配置文件链接
v2ray infolink 生成 V2Ray 配置信息链接
v2ray qr 生成 V2Ray 配置二维码链接
v2ray ss 修改 Shadowsocks 配置
v2ray ssinfo 查看 Shadowsocks 配置信息
v2ray ssqr 生成 Shadowsocks 配置二维码链接
v2ray status 查看 V2Ray 运行状态
v2ray start 启动 V2Ray
v2ray stop 停止 V2Ray
v2ray restart 重启 V2Ray
v2ray log 查看 V2Ray 运行日志
v2ray update 更新 V2Ray
v2ray update.sh 更新 V2Ray 管理脚本
v2ray uninstall 卸载 V2Ray

vmess 协议配置

查看配置文件(该配置在后面链接时使用)：
cat /etc/v2ray/config.json


【完整版 v2rayN 带核心 Github 下载地址】： https://github.com/2dust/v2rayN/releases/download/5.39/v2rayN-Core.zip
