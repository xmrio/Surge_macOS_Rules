# Surge_macOS_Rules

适配Surge 3.0,为方便更新,采用了模块规则,并优化了Dashboard的显示方式,方便查阅修改.


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
CIDR-NF = IP-CIDR-Netflix Service,
CIDR-Proxy = IP-CIDR-Proxy,
CIDR-REJECT = IP-CIDR-REJECT

#PROCESS-NAME
PN-DIRECT = PROCESS-NAME-DIRECT,
PN-Proxy = PROCESS-NAME-Proxy

#其他分流项目
#Apple(部分包含ATV流量分布)
PN-P-AS = PROCESS-NAME-Proxy-Apple Service,

D-AS = DOMAIN-Apple Service,
D-D-AS = DOMAIN-DIRECT-Apple Service,
DS-AS = DOMAIN-SUFFIX-Apple Service,
DS-D-AS = DOMAIN-SUFFIX-DIRECT-Apple Service,
DK-AS = DOMAIN-KEYWORD-Apple Service



#Netflix

DS-NS = DOMAIN-SUFFIX-Netflix Service,

PN-P-NS = PROCESS-NAME-Proxy-Netflix Service


#Apple TV(tvOS)

D-D-ATV = DOMAIN-DIRECT #Apple TV
D-P-ATV = DOMAIN-Proxy #Apple TV
UA-D-ATV = USER-AGENT,DIRECT #Apple TV
UA-P-ATV = USER-AGENT,Proxy #Apple TV




```
