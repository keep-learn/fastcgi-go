### Go模拟fastcgi  替代php-fpm

### 运行方式
`caddy run -config Caddyfile //启动webserver,类似nginx`
`go run main.go // 启动go程序
### 注意实现
* 使用nginx会hang住,暂未找到原因

### fastcgi-go
原项目地址: https://github.com/moodrain/fastcgi-go
