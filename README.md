# phputil
A PHP Util Package


# composer test
```
composer init
```

local:
```
composer config repositories.backtend path "D:\backtend\phputil"
composer require backtend/phputil:^1.0 -vvv

composer update backtend/phputil
```


本地开发composer包，若修改了composer.json需要重置：
```
composer remove backtend/phputil
composer require backtend/phputil
```


# 语义化版本
[Version Tips](https://semver.org/lang/zh-CN/)

```blade
1.0.0-alpha < 1.0.0-alpha.1 < 1.0.0-alpha.beta < 1.0.0-beta < 1.0.0-beta.2 < 1.0.0-beta.11 < 1.0.0-rc.1 < 1.0.0
```