# addStaticRoutes
A script for adding static routes on Mac OS X.

If you are using vpn but want to bypass it for local/domestic networks,
then this script is just what you're looking for.

**NOTE:**

1. *sudo* is needed for executing.
2. The addresses in the script are Chinese domestic networks with [CIDR](http://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing) notation.
Feel free to change them.

### 该脚本用于VPN路由分流， 即当访问国内IP的地址时会自动使用本地网关，可以节省VPN流量或绕过一些APP或网站对国外IP的封锁

#### 注意：
1. 脚本执行需要sudo 权限
2. 切换网络的时候需要重新执行一遍本脚步（因为大部分情况你的gateway变了）
