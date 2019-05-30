# ShadowSocks PAC过滤规则说

- 类型

  - DOMAIN-SUFFIX 

    根据域名的后缀判断

     如：“baidu.com”可以过滤tieba.baidu.com,pan.baidu.com 等，以baidu.com 为后缀的所有

  - DOMAIN-KEYWORD 

    根据关键字判断 

    如："baidu"，就可以过滤baidu.com,baidu.jp 等，包含有baidu字的网站

  - DOMAIN

    根据域名判断

    如：”www.baidu.com“ ,就可以过虑掉些网站

  - IP-CIDR

    判断是否为局域网

  - GEOIP

    判断服务器地址

  - USER-AGENT

  - URL-REGEX

    根据URL的正则表达式

    如：”*du.com“,可以过滤掉baidu.com,heidu.com等

  - FINAL

    剩余的网站

- 选项

  - PROXY

    代理

  - REJECT

    拒绝

  - DIRECT

    直连