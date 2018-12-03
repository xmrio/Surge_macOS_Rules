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

##PROCESS-NAME
PN-P-AS = PROCESS-NAME-Proxy-Apple Service,
PN-P-NS = PROCESS-NAME-Proxy-Netflix Service,
PN-DIRECT = PROCESS-NAME-DIRECT,
PN-Proxy = PROCESS-NAME-Proxy,
PN-REJECT = PROCESS-NAME-REJECT

##IP-CIDR
CIDR-AS = IP-CIDR-Apple Service,
CIDR-NS = IP-CIDR-Netflix Service,
CIDR-Proxy = IP-CIDR-Proxy,
CIDR-REJECT = IP-CIDR-REJECT



#其他分流项目

###Apple
PN-P-AS = PROCESS-NAME-Proxy-Apple Service,
D-AS = DOMAIN-Apple Service,
D-D-AS = DOMAIN-DIRECT-Apple Service,
DS-AS = DOMAIN-SUFFIX-Apple Service,
DS-D-AS = DOMAIN-SUFFIX-DIRECT-Apple Service,
DK-AS = DOMAIN-KEYWORD-Apple Service

###Netflix
D-P-NS = DOMAIN-Proxy-Netflix Service,
DS-P-NS = DOMAIN-SUFFIX-Proxy-Netflix Service,
DS-NS = DOMAIN-SUFFIX-Netflix Service

###ATV(分流配置完成)
UA-D-ATV = User-Agent-DIRECT-ATV,
UA-P-ATV = User-Agent-Proxy-ATV,
UA-P-JP-ATV = User-Agent-Proxy-JP-ATV

D-P-ATV = DOMAIN-Proxy-ATV,
D-P-JP-ATV = DOMAIN-Proxy-JP-ATV,
D-NS-ATV = DOMAIN-Proxy-NS-ATV

DS-P-ATV = DOMAIN-SUFFIX-Proxy-ATV,
DS-P-US-ATV = DOMAIN-SUFFIX-Proxy-US-ATV,
DS-NS-ATV = DOMAIN-SUFFIX-Proxy-NS-ATV


##烩菜Package

#####BBC
DS?-P-UK-BBC = DOMAIN&DOMAIN-SUFFIX-Proxy-UK-BBC

```





