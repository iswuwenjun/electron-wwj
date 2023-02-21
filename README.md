# electron-wwj

# 清空代理
git config --global --unset http.proxy
git config --global --unset https.proxy

# 配置VPN的代理端口
git config --global http.proxy 'socks5://127.0.0.1:1080'
git config --global https.proxy 'socks5://127.0.0.1:1080'

main分支
ipconfig /displaydns
ipconfig /flushdns