# QuantumultX-
# Quantumult X小白配置 制作 by Orz-3 TG频道：t.me/Orzmini 2021/08/26更新

[general]
server_check_url=http://cp.cloudflare.com/generate_204
dns_exclusion_list=*.cmpassport.com, *.jegotrip.com.cn, *.icitymobile.mobi, id6.me, *.pingan.com.cn, *.cmbchina.com
geo_location_checker=http://ip-api.com/json/?lang=zh-CN, https://raw.githubusercontent.com/Orz-3/Orz-3/master/QuantumultX/IP.js
resource_parser_url=https://cdn.jsdelivr.net/gh/KOP-XIAO/QuantumultX@master/Scripts/resource-parser.js
excluded_routes=239.255.255.250/32, 24.105.30.129/32, 185.60.112.157/32, 185.60.112.158/32, 182.162.132.1/32
fallback_udp_policy=direct
running_mode_trigger=filter, filter, wifi1:all_direct, wifi2: all_direct

[dns]
no-ipv6
server=119.29.29.29
address=/mtalk.google.com/108.177.125.188
server=/dl.google.com/119.29.29.29
server=/dl.l.google.com/119.29.29.29
server=/tplogin.cn/system
server=/tplinklogin.net/system
server=/melogin.cn/system
server=/falogin.cn/system
server=223.5.5.5
server=114.114.114.114
server=1.0.0.1
server=8.8.8.8
server=/*.taobao.com/223.5.5.5
server=/*.tmall.com/223.5.5.5
server=/*.alipay.com/223.5.5.5
server=/*.alicdn.com/223.5.5.5
server=/*.aliyun.com/223.5.5.5
server=/*.jd.com/119.28.28.28
server=/*.qq.com/119.28.28.28
server=/*.tencent.com/119.28.28.28
server=/*.weixin.com/119.28.28.28
server=/*.bilibili.com/119.29.29.29
server=/hdslb.com/119.29.29.29
server=/*.163.com/119.29.29.29
server=/*.126.com/119.29.29.29

[policy]
static=FsatFrog, resource-tag-regex=FastFrog, server-tag-regex=原生, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Star_1.png
static=HT, resource-tag-regex=Hutao, server-tag-regex=香港|新加坡|台湾, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Nfcloud.png
static=PRPR, resource-tag-regex=prpr, server-tag-regex=香港|新加坡, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Cat.png
static=xqcloud, resource-tag-regex=小强, server-tag-regex=^((?!台湾).)*$, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/AfreecaTV.png
static=Dxmax, resource-tag-regex=大炫max, server-tag-regex=香港.*NF|新加坡.*NF, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Alibaba.png
static=fwnnyy, resource-tag-regex=飞鸟云, server-tag-regex=香港.*奈飞|新加坡.*奈飞, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Blackhole.png
url-latency-benchmark=♻️ 自动选择, resource-tag-regex=yh, check-interval=600, tolerance=10, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Auto.png
static=电报消息, PROXY,img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Telegram.png
static=twiter, 美国节点, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Twitter.png
# 默认设置10分钟测速一次，当前使用节点延迟和最新测速延迟最低的节点相差100ms以上则切换为最新的最低延迟节点，否则继续延用节点
#static=Netflix, proxy, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netflix_Letter.png
static=全球加速, 香港节点, 台湾节点, 日本节点, 狮城节点, 美国节点, proxy, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Global.png
static=苹果服务, direct, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/App_Store.png
static=港台番剧, direct, 香港节点, 台湾节点, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/bilibili_4.png
static=国际媒体, 香港节点, 台湾节点, 日本节点, 美国节点, 狮城节点, proxy, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/YouTube.png
static=黑白名单, 全球加速, direct, 香港节点, 台湾节点, 日本节点, 狮城节点, 美国节点, proxy, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Final.png
url-latency-benchmark=香港节点, server-tag-regex=香港|香港.*NF|香港.*奈飞, check-interval=600, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/HK.png
url-latency-benchmark=台湾节点, server-tag-regex=台湾|台湾.*NF|台湾.*奈飞, check-interval=600, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/TW.png
url-latency-benchmark=日本节点, server-tag-regex=(?=.*(日|JP|(?i)Japan))^((?!(港|台|韩|新|美)).)*$, check-interval=600, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/JP.png
url-latency-benchmark=狮城节点, server-tag-regex=新加坡|新加坡.*NF|新加坡.*奈飞, check-interval=600, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/SG.png
url-latency-benchmark=美国节点, server-tag-regex=(?=.*(美|US|(?i)States|American))^((?!(港|台|日|韩|新)).)*$, check-interval=600, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/US.png
static=🚀 节点选择, ♻️ 自动选择, proxy, direct, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Available.png
static=🚫屏蔽系统更新, reject, direct, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Apple_Update.png
[server_remote]
https://subscribe.a9b.top/link/ym1ZkgYd2mQZMHVr?list=quantumultx#out=澳洲+印度+俄罗斯测试&rename=v1.主力.A.B.C.D.E.|.3.4.5.6.7.8.9.台负载.负载.混合☠️&sort=新加坡&台湾&日本, tag=FastFrog, update-interval=172800, opt-parser=true, enabled=true
https://sub.hutaomaster.com/link/GmVZB8GH45SMRRHD?sub=1, tag=Hutao, update-interval=172800, opt-parser=false, enabled=true
https://sub.prpr.hk/quanxudp/3324/N8Gr0ePI1N/, tag=prpr, update-interval=172800, opt-parser=false, enabled=true
https://xqcloud.net/api/v1/client/subscribe?token=4cc9340e41296350ea4d115217efc6ff&flag=quantumult%20x#rename=香港@HK+新加坡@SG+日本@JP+美国@USA+韩国@KR+VUL.VIP.AWS.01.02.03.04.中转.|☠️, tag=小强, update-interval=172800, opt-parser=true, enabled=true
https://feiniaoyun.tk/api/v1/client/subscribe?token=746c825ce54c7346718aab3868860051, tag=飞鸟云, update-interval=172800, opt-parser=false, enabled=true
https://dy.dxmax.top/api/v1/client/subscribe?token=4f0c15e7e26edeceb43663c29368fb1a, tag=大炫max, update-interval=172800, opt-parser=false, enabled=true

[filter_remote]
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/China.list, tag=中国路线, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/ChinaIP.list, tag=中国IP, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Global.list, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Unbreak.list, tag=规则修正, force-policy=direct, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Advertising.list, tag=广告拦截, force-policy=reject, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/NobyDa/Script/master/Surge/AdRule.list, tag=广告拦截, force-policy=reject, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Hijacking.list, tag=运营劫持, force-policy=reject, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Privacy.list, tag=隐私保护, force-policy=reject, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Video/TikTok.list, tag=海外抖音, force-policy=全球加速, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/HK.list, tag=流媒体HK, force-policy=香港节点, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/TW.list, tag=流媒体TW, force-policy=台湾节点, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/JP.list, tag=流媒体JP, force-policy=日本节点, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/US.list, tag=流媒体US, force-policy=美国节点, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Streaming.list, tag=国际媒体, force-policy=国际媒体, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/StreamingSE.list, tag=港台番剧, force-policy=港台番剧, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Global.list, tag=全球加速, force-policy=全球加速, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/AppStore.list, tag=苹果服务, force-policy=苹果服务, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/AppStoreConnect.list, tag=苹果服务, force-policy=苹果服务, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/TestFlight.list, tag=Testflight, force-policy=苹果服务, update-interval=86400, opt-parser=true, enabled=true

[rewrite_remote]
https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Q-Search_All_in_one.conf, tag=Q-Search, enabled=true


https://raw.githubusercontent.com/app2smile/rules/master/module/spotify.conf, tag=Spotify, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/zwf234/rules/master/QuantumultX/qxrules.conf, tag=奇心规则合集, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/zwf234/rules/master/QuantumultX/price.conf, tag=京东淘宝比价, update-interval=86400, opt-parser=false, enabled=true

https://raw.githubusercontent.com/zwf234/rules/master/QuantumultX/tailadv.conf, tag=去开屏广告, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/chavyleung/scripts/master/box/rewrite/boxjs.rewrite.quanx.conf, tag=boxjs, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/YouTube.conf, tag=YouTube, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/CzY0913/Quanx-Surge/main/Quanx/Advertising/smzdm_remove_ads.qxrewrite, tag=bilibili去广告, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/TikTok.conf, tag=Tiktok解锁, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/Bili_Auto_Regions.conf, tag=哔哩哔哩自动换区, update-interval=86400, opt-parser=false, enabled=false
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/JS.conf, tag=Script, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/JS_GetCookie.conf, tag=Cookie, update-interval=86400, opt-parser=false, enabled=false
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/Block/Advertising.conf, tag=神机去广告, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/Rewrite_lhie1.conf, tag=lhie1去广告, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/General.conf, tag=神机重定向, update-interval=86400, opt-parser=false, enabled=true

[server_local]

[filter_local]
#去掉YouTube++底部广告
host-suffix, ehg-youtube.hitbox.com, reject
host, mesu.apple.com, 🚫屏蔽系统更新
host, gdmf.apple.com, 🚫屏蔽系统更新

host-suffix, ehg-youtube.hitbox.com, reject
host-suffix, local, direct
ip-cidr, 192.168.0.0/16, direct
ip-cidr, 10.0.0.0/8, direct
ip-cidr, 172.16.0.0/12, direct
ip-cidr, 127.0.0.0/8, direct
ip-cidr, 100.64.0.0/10, direct
ip-cidr, 224.0.0.0/4, direct
ip6-cidr, fe80::/10, direct
ip-cidr, 203.107.1.1/24, reject
-geoip, cn, direct
final, 黑白名单

[rewrite_local]
https:cloud.faster.buzz url script-request-header https://raw.githubusercontent.com/evilbutcher/Quantumult_X/master/check_in/glados/checkincookie_env.js
^https?:\/\/mp\.weixin\.qq\.com\/mp\/getappmsgad url script-response-body https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/Wechat.js
daojia.jd.com/html/index.html url script-request-header https://raw.githubusercontent.com/passerby-b/JDDJ/main/jddj_getck.js 

^https:\/\/(api\.m|me-api)\.jd\.com\/(client\.action\?functionId=signBean|user_new\/info\/GetJDUserInfoUnion\?) url script-request-header https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js
https:\/\/ap(p|i)\.bilibili\.com\/((pgc\/player\/api\/playurl)|(x\/v2\/account\/myinfo\?)|(x\/v2\/account/mine\?)) url script-response-body https://raw.githubusercontent.com/Sunert/Script/master/Script/Bilibili/BiliHD.js
https?:\/\/(www.)?(g|google)\.cn url 302 https://www.google.com
^https?:\/\/mp\.weixin\.qq\.com\/mp\/getappmsgad url script-response-body https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/Wechat.js

[task_local]
5 0 * * * https://raw.githubusercontent.com/evilbutcher/Quantumult_X/master/check_in/glados/checkincookie_env.js
25 8 * * * https://raw.githubusercontent.com/NobyDa/Script/master/KuaiKan-DailyBonus/KKMH.js, tag=快看漫画签到, img-url=https://raw.githubusercontent.com/NobyDa/mini/master/Color/KuaiKan.png, enabled=true
event-interaction https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/nf_ytb_ui-check.js, tag=YouTube/Netflix 解锁查询, img-url=checkmark.seal.system, enabled=true
event-interaction https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/geo_location.js, tag=GeoIP 查询, img-url=location.fill.viewfinder.syste
0 8-22/3 * * * https://raw.githubusercontent.com/Peng-YM/QuanX/master/Tasks/nCov.js, tag=疫情动态, img-url=https://qxnav.com/rules/QuantumultX/img/COVID-19.png, enabled=true
55 23 * * * https://qxnav.com/rules/QuantumultX/js/jd_unsubscribe.js, tag=取关京东店铺商品, img-url=https://qxnav.com/rules/QuantumultX/img/jd.png, enabled=false
10 12,18 * * * https://raw.githubusercontent.com/id77/QuantumultX/master/task/jdWuLiu.js, tag=京东物流派件提醒, img-url=https://qxnav.com/rules/QuantumultX/img/jd.png, enabled=true
2 9 * * * https://qxnav.com/rules/QuantumultX/js/jd_bean_change.js, tag=京豆变动通知, img-url=https://qxnav.com/rules/QuantumultX/img/jd.png, enabled=false
3 0 * * * https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js, tag=京东多合一, img-url=https://qxnav.com/rules/QuantumultX/img/jd.png, enabled=false



[http_backend]
https://raw.githubusercontent.com/chavyleung/scripts/master/chavy.box.js, tag=boxjs, path=^/, enabled=true

[mitm]
passphrase = 0AE94422
p12 = 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
skip_validating_cert = true
hostname = *cloud.faster.buzz, mp.weixin.qq.com,ms.jr.jd.com, me-api.jd.com, api.m.jd.com,api.bilibili.com,daojia.jd.com,*cloud.faster.buzz

 
