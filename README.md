# proxycn
something about proxy tools.

提到科学上网，懂的人都懂。对于搞外贸的、搞技术研究的人等等是必不可少的。
科学上网的原理及介绍： introduce

常用的技术并不是VPN技术，准确地来讲是proxy技术，代理技术，将目标网站的内容获取后，加密传输给你，从而避开审查。
一般来讲主要有两种方式，一种是购买他人提供的proxy服务，一种是自行搭建proxy
购买成熟的服务费钱，自已搭服务器费时间。
表格：
个人根据情况进行选择。


一、常用的proxy服务（即所谓的VPN)包括：
1.StrongVPN
2.ExpressVPN 
3.justMysocks.net https://justmysocks.net/members/aff.php?aff=24386
JMS由搬瓦工2018年推出。据说主要优点有两个：1、流量稳定靠谱。2、付款方便，支持银联卡、PayPal和支付宝。

二、自建proxy服务
1.介绍总体技术路线
SS是绝对不能选择的，很容易被识别，导致服务器被封IP。

WireGuard协议只有官网下载安装的标准版客户端提供，但是根据部分读者反映，WireGuard协议在国内使用不稳定，会出现显示连接却上不了网的情况，比较鸡肋，有时候不如使用OpenVPN协议稳定。




部署流程：
购买VPS -> 申请域名和证书  -> 部署服务 -> 选择合适的客户端




2.VPS的选择
新手最早看到的都是用搬瓦工和vultr，搬瓦工最便宜也要49$/年，vultr更是需要60$/年。

DMIT：自成立以来，DMIT便是土豪商家的代表，资费不便宜。今年7月DMIT收购HKServerSolution国际站部分业务后，成为CN2 GIA VPS的大鳄，CN2带宽充足（搬瓦工有时也会向DMIT购买带宽）。产品质量和稳定性都比较有保障，适合想省心不折腾的网友，本站目前也托管在此。季付、半年付、年付产品可使用DMIT优惠码 DMIT59CUGN 续费优惠5%。官网：https://www.dmit.io，购买建议参考：DMIT服务器购买和使用教程；

racknerd.com  https://my.racknerd.com/aff.php?aff=3278 
RackNerd，距今为止已成立3年，国外商家（老板基本可以确定是华人），国外知名VPS平台便宜VPS类票选的2020年TOP10商家，2021年度TOP3商家。因为其高性价比VPS的特色，以及迅速及时的工单服务，在国外和国内用户中热度都很高，知名度连年攀升。商家官网有繁体中文版，并支持国内的支付宝，微信，以及国外主流的PayPal、信用卡等付款方式。
前两年因为有传言说老板是跑路四大金刚，RackNerd是灵车，因此和RackNerd迅速蹿升的知名度伴随着的，还有巨大的争议。不过由于这几年RackNerd持续稳定的服务，这类传言也逐渐销声匿迹。
点击https://www.racknerd.com/BlackFriday/ 这个页面购买优惠的VPS。 首页上点击的话，
https://www.racknerd.com/NewYear/  这样的页面购买才划算。这个页面可能会随着时间变化，大家可以在网上搜索一下，用这样的优惠链接打开进行购买。




3.申请域名和证书
这里只讲免费的证书申请网站，
freenom.com 可以申请.tk  .cf ，申请方法参考这个链接 ： https://zhujitips.com/328
免费的域名解析网站， 1.2.3.4.sslip.io  将自动解析到1.2.3.4这个IP地址，非常好用。https://sslip.io/   https://nip.io/
收费的就不用说了。

域名申请脚本：





4.部署服务 

ss 不要再使用了，包括SSR也不要使用。
kcptun也不能使用了，使用必被封。



trojan-go
v2ray  https://github.com/XTLS/Xray-core
https://github.com/v2fly/v2ray-core

gost




5.客户端的选择
windows
linux
android
ios




6.一键部署流程

一键脚本有可能暗藏挖矿木马，使用需谨慎。
https://github.com/wulabing/Xray_onekey




7.一些免费节点
网友们可能会遇到先有鸡还是先有蛋的问题，就是你要部署科学上网的服务的时候，需要通过科学上网来实现。
此时可以先借用一下免费的节点完成工作，完成后再用自己的节点。毕竟免费的节点使用的人太多，速度上会比较慢，并且一直在更新，也缺乏稳定性。

freefq https://github.com/freefq/free
可以使用以下地址进行订阅：

https://raw.fastgit.org/freefq/free/master/v2
https://ghproxy.com/https://raw.githubusercontent.com/freefq/free/master/v2
还有这个站点：
https://free-ss.site/
https://github.com/aiboboxx/v2rayfree


8.更多的科学上网相关知识
https://crifan.github.io/scientific_network_summary/website/
tlanyan 有一些部署方法介绍 https://itlanyan.com/
  
目前最重要的科学上网工具：Xray官方文档
https://xtls.github.io/

https://www.v2fly.org/ v2fly官方网站


