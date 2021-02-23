**检测你的vps是否解锁Netflix**
------------------

一键脚本，来自于网络
------------------

全部复制以下代码到服务回车就行

    yum install -y curl 2> /dev/null || apt install -y curl\
    && bash <(curl -sSLhttps://github.com/fyglinfo/Netflix-/blob/main/nf.sh)
