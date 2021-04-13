# 微信

##### 1.导入代码，使用composer
```php
composer required GlennZZ/wechat:dev-master
```

##### 2.开始使用
```php
require 'vender/autoload.php';
$wechat = new \GlennZZ\wechat\Wechat([
    'appId' => '',
    'appSecret' => '',
    'mchId' => '',
    'apiKey' => '',
    'certPem' => '',
    'keyPem' => '',
    'cachePath' => '',
]);
$wechat->getAccessToken();
```
