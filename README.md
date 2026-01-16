# ss2anytls-autodeploy

通过sing-box内核，一键部署在公网服务器B和服务器C之间 ss-anytls 隧道。
Autodeploy ss-anytls tunnel between server B &amp; C with sing-box core.

## 一键脚本

```
curl -O https://raw.githubusercontent.com/Cyli00/ss2anytls-autodeploy/refs/heads/main/autodeploy.sh
chmod +x autodeploy.sh
bash autodeploy.sh
```

## 建议流程 
1. **在服务器 C** 运行脚本 → 选择 `[2] (Exit)`
2. 复制显示的 IP、Port、Password
3. **在服务器 B** 运行脚本 → 选择 `[1] (Relay)`
4. 粘贴 C 的信息，设置本地端口和节点名称
5. 获得 SS URI 链接，分享给用户直接导入！
