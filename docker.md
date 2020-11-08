#### 启动docker
```sudo systemctl start docker```

#### 用bash运行
```docker run -it centos /bin/bash```

#### 启动容器
```docker start image```

#### 进入已启动容器
```docker attach image```

#### 保存修改后容器
```docker commit -a="作者" -m="注释" 容器 容器名:版本号```

```sudo docker exec -it 53148439ac91 /bin/bash```

#### 主机端口：docker里的端口
```-p 1234:80```

```docker rm -f $(docker ps -aq)```

```docker rmi -f $(docker images -aq)```