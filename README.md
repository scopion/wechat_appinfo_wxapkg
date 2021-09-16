# wechat_appinfo_wxapkg
 渗透测试：微信小程序信息在线收集，wxapkg源码包内提取信息

**两个在线搜索信息的脚本**

`wechat_app_search.py	批量搜索微信小程序`

`wechat_domains_search.py	批量搜索微信小程序域名`

这两个来源于	https://www.hackinn.com/index.php/archives/672/

**一个搜索wxapkg源码包（反编译后）内敏感信息的脚本**

`wechat_wxapkg_infoget.py	微信小程序源码包wxapkg内部链接提取 v2.0`

内部加入了【findsomething】这个项目的规则，可以匹配手机号、身份证、jwt、url、ip、domain、apikey、user|password等字符串

