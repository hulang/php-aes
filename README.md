### 文件/文件夹操作类

### 使用composer进行安装
~~~
composer require hulang/php-aes
~~~

### 使用composer进行更新
~~~
composer update hulang/php-aes
~~~

### 引入类文件
~~~
use hulang/Aes;
~~~

### 使用说明
~~~
use hulang/Aes;
$aes = new Aes('密匙');
加密
$res = $aes->encode('要加密的字符串');
解密
$res = $aes->decode('要解密的字符串');
~~~
