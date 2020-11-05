# Rules

```
##- DOMAIN-SUFFIX,google.com,Proxy 匹配域名后缀(交由Proxy代理服务器组)
##- DOMAIN-KEYWORD,google,Proxy 匹配域名关键字(交由Proxy代理服务器组)
##- DOMAIN,google.com,Proxy 匹配域名(交由Proxy代理服务器组)
##- DOMAIN-SUFFIX,ad.com,REJECT 匹配域名后缀(拒绝)
##- IP-CIDR,127.0.0.0/8,DIRECT 匹配数据目标IP(直连)
##- SRC-IP-CIDR,192.168.1.201/32,DIRECT 匹配数据发起IP(直连)
##- DST-PORT,80,DIRECT 匹配数据目标端口(直连)
##- SRC-PORT,7777,DIRECT 匹配数据源端口(直连)
```

https://raw.githubusercontent.com/mlgitsaver/Rules/private/clash/Direct.yaml
https://raw.githubusercontent.com/mlgitsaver/Rules/private/clash/Proxy.yaml

https://cdn.jsdelivr.net/gh/mlgitsaver/Rules@private/clash/Direct.yaml
https://cdn.jsdelivr.net/gh/mlgitsaver/Rules@private/clash/Proxy.yaml

