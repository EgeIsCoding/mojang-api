[![Software License][ico-license]](LICENSE.md)

```bash
composer require ely/mojang-api
```

```php
<?php
$api = new \Ely\Mojang\Api();
$response = $api->usernameToUUID('erickskrauch');
echo $response->getId();
```


```bash
$ ./vendor/bin/phpunit
```
