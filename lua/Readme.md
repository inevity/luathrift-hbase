# confiure command
./configure --prefix=/usr/local/thrift10lua51 --without-qt4 --without-qt5
--without-dart --without-haxe --without-c_glib --without-csharp --without-erlang
--without-nodejs --without-python --without-perl --without-php
--without-php_extension --without-ruby -without-haskell --without-go --without-d
--with-lua --without-cpp LDFLAGS=-L/usr/local/openresty/luajit/lib/
LUA=/usr/local/openresty/luajit/bin/luajit
LUA_INCLUDE=-I/usr/local/openresty/luajit/include/luajit-2.1
LUA_LIB=-lluajit-5.1
thrift --gen lua /root/hbase/hbase-thrift/src/main/resources/org/apache/hadoop/hbase/thrift2/hbase.thrift
