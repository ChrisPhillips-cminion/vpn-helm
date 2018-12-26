# vpn-helm

*BETA*

This is simple chart to put a VPN Server into your kubernetes environment. 


The values file must contain these entries
```
VPN_IPSEC_PSK: shared-password
VPN_USER: cminion
VPN_PASSWORD: password
#Public IP
EXTERNALIP: 1.1.1.1
```


* VPN_IPSEC_PSK - The share password
* VPN_USER - username
* VPN_PASSWORD - User Password
