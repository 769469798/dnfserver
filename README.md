DNFServer
==**centos 7.6**==
## 服务端
`fullpackage.tar.gz`
`install`
上传到cd /
```shell
chmod 777 /install;/install
```
安装完成后
等级补丁,密钥,PVF(未加密)拖入以下位置
`home/neople/game`
## 登录器下载
 Base64
`aHR0cHM6Ly9wYW4uYmFpZHUuY29tL3MvMVZlcWRCZVZZSXd2amxiM0NoMG5ibHc/cHdkPTFtZDg=`
安装网关
```shell
curl -O https://gitee.com/baoyut/by/raw/master/bywg;chmod +x bywg;./bywg
```

**将登录器中网关文件覆盖至服务器/根目录**

```shell
sudo chmod -R 777 /root
```
```sh
sudo chmod -R 777 /home
```

停止服务端
`cd /root;./stop;./stop`

启动服务端跑五国
`./stop;./stop;./run`


启动网关
`./Restart`

## 客户端
准备一个台服客户端
Base64
`aHR0cHM6Ly9wYW4uYmFpZHUuY29tL3MvMU55RnJLSnJKX21FaWNIaktVZUIxOHc/cHdkPWEyanE=`

只保留目录内文件夹

将登录器中客户端文件全部拖入覆盖
登录后台生成授权文件,更改配置后加密的pvf文件拖入客户端内
