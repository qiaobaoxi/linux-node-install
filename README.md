# linux-node-install
进入服务器

输入命令：·wget https://npm.taobao.org/mirrors/node/v8.9.3/node-v8.9.3-linux-x64.tar.xz

                        ·xz -d node-v8.9.3-linux-x64.tar.xz  或者  tar -xzvf node-v8.9.3-linux-x64.tar.gz

                      ·tar -xvf node-v8.9.3-linux-x64.tar

                     ·ln -s /node-v8.9.3-linux-x64/bin/node /usr/local/bin/node

                     ·ln -s /node-v8.9.3-linux-x64/bin/npm/usr/local/bin/npm

(提示：最后两步需要在根目录执行)

输入命令：node -v  出现版本号即安装成功

                       npm -v   出现版本号即安装成功

 

