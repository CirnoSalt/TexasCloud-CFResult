### 云上德州定制节点
参考下面的教程，基于你的网络环境定制专属节点。

1：从群文件下载测速工具

2：根据你的网络情况双击运行【开始优选v4.bat】或【开始优选v6.bat】   
注意路由器性能较差可能导致运行过程中路由器死机，尤其IPV6脚本！

3：稍等一会，脚本会自动根据你的网络情况找出最优的赛博活佛节点，按下回车，结果将自动上传至本仓库的【[cloudflare_ips.txt](https://github.com/CirnoSalt/TexasCloud-CFResult/blob/main/cloudflare_ips.txt)】文件中。
<img width="1644" height="682" alt="image" src="https://github.com/user-attachments/assets/987b383c-58ed-40fa-9d9d-b235732ab90d" />
<img width="1388" height="468" alt="image" src="https://github.com/user-attachments/assets/4c93fde1-b305-4c3b-9009-ebc0ffe73458" />
   
4：打开[这个](https://bp.sub.cmliussss.net/)链接，按照下面的指示填写：
```
===代理域名设置===
HOST：snippetprx.cirno9.ggff.net
源码版本：白嫖哥源码
UUID：a02c197a-aa53-473d-a0bb-e7f78d116367

===优选IP设置===
优选IP模式：自定义优选IP
优选IP列表：复制粘贴本仓库的【cloudflare_ips.txt】文件中的内容

===落地IP设置===
链接方式：ProxyIP模式
ProxyIP地址：ProxyIP.DigitalOcean.CMLiussss.net

===订阅转换设置===
用于Clash系软件的设置，无特殊需要一般保持默认即可。

===节点高级设置===
保持默认即可。
```
填写完上面的内容然后点击【生成订阅】按钮，如无意外将会显示专属于你的定制节点订阅链接，
支持Clash、V2rayN等常用工具，不建议将这个订阅分享给他人，因为脚本是基于你当前的网络环境优选的节点。
