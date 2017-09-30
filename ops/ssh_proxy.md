## SSH Configuration Proxy commands
```
## gojira.kfc.douglas-enterprises.com
Host gojira
HostName 10.0.1.11 
User sdouglas 
ProxyCommand ssh -p 2562 sdouglas@kfc.douglas-enterprises.com nc %h %p

## donchor.ava.sea.douglas-enterprises.com
Host donchor 
HostName donchor 
User sdouglas 
ProxyCommand ssh -p 2561 sdouglas@ava.sea.douglas-enterprises.com nc %h %p
```

