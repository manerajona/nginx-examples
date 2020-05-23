# nginx-examples

### Edit *nginx.conf* file
```sh
$  sudo find / -name "nginx.conf"
$  cd /etc/nginx/ 
$  sudo mv nginx.conf nginx.conf.bkp
$  sudo nano nginx.conf
```

### Commands
#### start
$ sudo nginx

#### stop
$ sudo nginx -s stop

#### apply changes
$ sudo nginx -s reload
