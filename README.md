# Linux内核编译
1.-**安装必要软件**-

     sudo yum install -y gcc elfutils-libelf-devel ncurses-devel bc openssl-devel flex bison
2.-**编写脚本**-
```shell
#!/bin/bash
sudo install -y gcc elfutils-libelf-devel ncurses-devel bc openssl-devel flex bison
```
3.多线程编译
     make -j(线程数)