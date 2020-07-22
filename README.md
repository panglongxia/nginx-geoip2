install libmaxminddb
```
wget https://github.com/maxmind/libmaxminddb/releases/download/1.3.2/libmaxminddb-1.3.2.tar.gz
tar -zxvf libmaxminddb-1.3.2.tar.gz
cd libmaxminddb-1.3.2/
./configure
make install
echo /usr/local/lib  >> /etc/ld.so.conf.d/local.conf
ldconfig
```
install  ngx_http_geoip2_module
```
wget https://github.com/leev/ngx_http_geoip2_module/archive/3.3.zip
./configure -add-module=gx_http_geoip2_module-3.3
make && make install
```


