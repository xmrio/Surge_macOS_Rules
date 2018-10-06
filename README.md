# Surge_macOS_Rules

适配Surge 3.0,为方便更新,采用了分离式的规则,并优化了Dashboard的显示方式,方便查阅修改.


```
如需要查阅对应的以下是缩写清单:

#DIRECT
D-DIRECT = DOMAIN-DIRECT,
DS-DIRECT = DOMAIN-SUFFIX-DIRECT,
DK-DIRECT = DOMAIN-KEYWORD-DIRECT

#REJECT
D-REJECT = DOMAIN-REJECT,
DS-REJECT = DOMAIN-SUFFIX-REJECT,
DK-REJECT = DOMAIN-KEYWORD-REJECT

#Proxy
D-Proxy = DOMAIN-Proxy,
DS-Proxy = DOMAIN-SUFFIX-Proxy,
DK-Proxy = DOMAIN-KEYWORD-Proxy

#IP-CIDR
CIDR-AS = IP-CIDR-Apple Service,
CIDR-Proxy = IP-CIDR-Proxy,
CIDR-REJECT = IP-CIDR-REJECT

#PROCESS-NAME
PN-DIRECT = PROCESS-NAME-DIRECT,
PN-Proxy = PROCESS-NAME-Proxy
```