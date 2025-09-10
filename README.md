### 使用cloudflare 大善人 workers 或者 pages 部署后你也可以拥有跟这个网站一样的功能
傻瓜式 节点已经复活  支持 vless  trojan  ss  同时还支持 /OTC/156.244.1.250:8443  格式反代 及 /OTC/TW 格式反代    提供手搓实例
### 实例1 傻瓜式自动反代对应国家 比如 US 、 HK 、 CN 、TW 等等等
```
vless://aaaaaaaa-bbbb-4ccc-8ccc-dddddddddddd@xxxxxxxx.tk.cdn.cloudflare.net:443?encryption=none&security=tls&sni=域名&fp=randomized&allowInsecure=1&type=ws&host=域名&path=%2FOTC/TW1#OTC
```
### 实例2 手工维护反代IP+端口
```
vless://aaaaaaaa-bbbb-4ccc-8ccc-dddddddddddd@xxxxxxxx.tk.cdn.cloudflare.net:443?encryption=none&security=tls&sni=域名&fp=randomized&allowInsecure=1&type=ws&host=域名&path=%2FOTC/156.244.1.250:8443#OTC
```
### 实例3 傻瓜式自动反代对应国家 比如 US 、 HK 、 CN 、TW 等等等
```
trojan://aaaaaaaa-bbbb-4ccc-8ccc-dddddddddddd@xxxxxxxx.tk.cdn.cloudflare.net:443?security=tls&sni=域名&fp=randomized&allowInsecure=1&type=ws&host=%E5%9F%9F%E5%90%8D&path=%2FOTC/TW1#OTC
```
### 实例4 手工维护反代IP+端口
```
trojan://aaaaaaaa-bbbb-4ccc-8ccc-dddddddddddd@xxxxxxxx.tk.cdn.cloudflare.net:443?security=tls&sni=域名&fp=randomized&allowInsecure=1&type=ws&host=%E5%9F%9F%E5%90%8D&path=%2FOTC/156.244.1.250:8443#OTC
```
### UUID 没去做固定 只要符合 V4 就能用
