# simple-ext

1.linux服务器上安装扩展前需包装安装了autoconf先： yum install autoconf
2.cd simple-ext
3.扩展安装
```
/usr/local/php7/bin/phpize  根据自己phpize的位置来运行即可（不知道phpize在哪的直接 find / -name phpize 查找）
# 编译扩展模块
./configure --with-php-config=/usr/local/php7/bin/php-config
make
make install
```