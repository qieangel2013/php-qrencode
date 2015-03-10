# php-qrencode

基于libqrencode+libgd的生成二维码的php扩展


## 安装:
git clone https://github.com/Leon2012/php-qrencode

cd php-qrencode

phpize

./configure

make&sudo make install

vi php.ini


## 用法:

$resource = qrencode_create("test");

qrencode_save($resource, "/Users/kentchen/Downloads/t3.png");//保存文件

echo qrencode_version()."\n";//查看版本号