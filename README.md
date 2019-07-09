@@ -1,18 +1 @@
＃  v2ray一键部署heroku [！[ Deploy ]（https://www.herokucdn.com/deploy/button.png）]（https://heroku.com/deploy?template=https://github.com/ wangyi2005 / v2ray-的Heroku）
V2ray-Core 3.9

1.服务端部署后，应打开app，显示Bad Request，表示部署成功。

2.客户端应用websocket + tls传输协议.Vmess协议的用户ID应当换成自己的UUID，“alterId”：64
＃  v2ray部署在openshift starter
openshift：内存设置为256M，每个项目可配置4个。

Docker镜像：wangyi2005 / v2ray：最新，wangyi2005 / v2ray：core版本号

环境变量：CONFIG_JSON（配置），CERT_PEM（证书），KEY_PEM（私钥）

用notepad ++将上述变量中\ r \ n替换为\\\ n，变成一行，导入容器。

客户端：android Actinium，windows v2ray可用同一个服务端。

具体配置：见问题。
