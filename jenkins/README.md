相关文档
https://hub.docker.com/r/jenkins/jenkins/
https://github.com/jenkinsci/docker/blob/master/README.md



# jenkins搭建

1.start.sh变为可执行文件
```shell
chmod +x start.sh
```

2.运行脚本
```shell
./start.sh
```

3.输入地址
```shell
http://localhost:8080/
```

4.账户密码
```shell
cat /Users/guoyoujin/DockerLib/jenkins/home/secrets/initialAdminPassword   #注意你自己的根目录位置
```