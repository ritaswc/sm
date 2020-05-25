#国密算法

#####使用方法

```php
$helper = new \Ritaswc\SM\SM4();
echo $helper->encrypt('this is key', 'PHP是世界上最好的语言');
echo "\n";
echo $helper->decrypt('this is key', 'TFK6KUnXe7/DLovioxZvU8G8GwcxXTf93GxR0mMiFts=');
```
#####结果是
```shell script
php index.php

TFK6KUnXe7/DLovioxZvU8G8GwcxXTf93GxR0mMiFts=
PHP是世界上最好的语言
```

## Author
- [Charles的小星球](https://blog.yinghualuo.cn)

## License
SM is licensed under [MIT](https://github.com/ritaswc/zx_ip_address/blob/master/LICENSE).