# Surge_macOS_Rules

适配Surge 3.0,为方便更新,采用了模块规则,并优化了Dashboard的显示方式,方便查阅修改.

如需要查阅对应的以下是缩写清单:

```
##DIRECT
D-DIRECT = DOMAIN-DIRECT,
DS-DIRECT = DOMAIN-SUFFIX-DIRECT,
DK-DIRECT = DOMAIN-KEYWORD-DIRECT

##REJECT
D-REJECT = DOMAIN-REJECT,
DS-REJECT = DOMAIN-SUFFIX-REJECT,
DK-REJECT = DOMAIN-KEYWORD-REJECT

##Proxy
D-Proxy = DOMAIN-Proxy,
DS-Proxy = DOMAIN-SUFFIX-Proxy,
DK-Proxy = DOMAIN-KEYWORD-Proxy

##IP-CIDR
CIDR-AS = IP-CIDR-Apple Service,
CIDR-NS = IP-CIDR-Netflix Service,
CIDR-Proxy = IP-CIDR-Proxy,
CIDR-REJECT = IP-CIDR-REJECT

##PROCESS-NAME
PN-P-AS = PROCESS-NAME-Proxy-Apple Service,
PN-P-NS = PROCESS-NAME-Proxy-Netflix Service,
PN-DIRECT = PROCESS-NAME-DIRECT,
PN-Proxy = PROCESS-NAME-Proxy,
PN-REJECT = PROCESS-NAME-REJECT

#其他分流项目

###Apple(部分包含ATV流量分布)


PN-P-AS = PROCESS-NAME-Proxy-Apple Service,
D-AS = DOMAIN-Apple Service,
D-D-AS = DOMAIN-DIRECT-Apple Service,
DS-AS = DOMAIN-SUFFIX-Apple Service,
DS-D-AS = DOMAIN-SUFFIX-DIRECT-Apple Service,
DK-AS = DOMAIN-KEYWORD-Apple Service



###Netflix
D-P-NS = DOMAIN-Proxy-Netflix Service,
DS-NS = DOMAIN-SUFFIX-Netflix Service,
DS-P-NS = DOMAIN-SUFFIX-Proxy-Netflix Service


##烩菜Package

#####BBC
P-P-BBC = Package-Proxy-BBC

```





