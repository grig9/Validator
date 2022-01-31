# Validator
Простой валидатор.

## Использование.

создать объект Validator
```php
$validator = new Validator();
```
Проверка email
```php
$validator->isEmail('Example@mail.com'); //return true or false
```
Проверка на вхождение длины строки в указанный диапазон от 10 до 20
```php
$validator->inLength('asfxcvzxcf', 10, 20); //return true or false
```
Проверка на вхождение числа в указанный диапазон от 120 до 240
```php
$validator->inRange(223, 120, 240); //return true or false
```
Проверка на корректный домен
```php
$validator->isDomain('www.yandex.ru'); //return true or false
```
