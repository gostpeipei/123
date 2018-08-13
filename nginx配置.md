## 三个需要记住的目录 /usr/local/cellar  /usr/local/etc/nginx  /usr/local/var
## 进入/usr/local/etc/nginx目录下，执行 sudo vim nginx.conf
### `user` 后第一个参数是用户名，第二个是用户组
### `location` 
    location / {   
        root html文件所在目录
        index index.html
    }

    配置接口
    location /wm/{
        proxy_pass http://115.159.219.170:8081/;
    }