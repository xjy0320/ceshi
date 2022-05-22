# 说明


修复青龙白屏
bpxf.sh、index.html、js.tar.gz 为备份文件

目前已知v2.11.2版及以上均不会白屏，如果有中招的玩家建议重装面板。或者尝试找回对应版本的index.html文件。
一键白屏修复命令：

ssh登录连接到终端，使用bash进入容器内
例如：进入名为qinglong的容器内部
docker exec -it qinglong bash
再整段复制下面的命令执行即可

bash <(curl -ls https://gitee.com/suiyuehq/ziyong/raw/master/ql_cdn/v2.10.13/bpxf.sh)
