# GDOCK
自动从lean的lede源码clone并生成竞斗云固件

*将本项目fork到自己账号下,进行以下操作即可得到专属定制固件*

1.diy.sh
可以编辑自定义和修改的脚本,可以直接修改JK预留的脚本,也可以自己编写

2.gdockfull128.config
编辑自定义配置文件.

3.以上修改完后push一下,即可自动编译固件，就是把yml文件中


on: 
  release:
    types: [published]
#  push:
#    branches: 
#      - master


上面3行的 # 都删除，就开始编译了。


如果你只想使用固件,可以在本项目的actions下下载最新编译的固件.

==============================================

![](/screenshots/r619ac1.png)

==============================================

部分脚本内容参考以下项目特此感谢:
https://github.com/P3TERX/Actions-OpenWrt/
