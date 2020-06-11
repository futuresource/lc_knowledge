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