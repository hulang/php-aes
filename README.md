### 使用AES加密算法进行数据加密和解密
PHP版本>=7.2.0

### 使用composer进行安装
~~~
composer require hulang/php-aes
~~~

### 使用composer进行更新
~~~
composer update hulang/php-aes
~~~

### 引入命名空间
~~~
use hulang/Aes;
$aes = new Aes('密匙');
加密
$res = $aes->encode('要加密的字符串');
解密
$res = $aes->decode('要解密的字符串');
~~~
