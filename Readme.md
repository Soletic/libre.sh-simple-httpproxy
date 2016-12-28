# Simple Http proxy for LibrePaaS

[Module HAProxy from Indieshosters](https://github.com/indiehosters/haproxy/) requires a valid domain to generate certificates SSL. So it's a problem to use it locally with a virtual machine. This http proxy module is a solution.

## Install

```
coreos> mkdir /data/certs
coreos> cd /system
coreos> git clone https://github.com/Soletic/libre.sh-simple-httpproxy.git ./httproxy
coreos> cd httpproxy
coreos> libre enable
coreos> libre start
```