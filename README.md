1.Dockerfile-php5.6是基于官方镜像php-5.6fpm生成的，加入了常用的php扩展包括gd、mcrypt、sockets、bcmath、soap、ssh2、mysql、mysqli、redis、memcache、memcached。
2.其中COPY ./php/conf/php.ini /usr/local/etc/php/php.ini可使用本地配置代替docker里面php的配置，可自行修改
3.若需要其他扩展，请自行重新修改。
