Простой валидатор.

Использование.

$validator = new Validator();

// Проверка email

$validator->isEmail('Example@mail.com'); //return true or false

// Проверка на вхождение длины строки в указанный диапазон от 10 до 20

$validator->inLength('asfxcvzxcf', 10, 20); //return true or false

// Проверка на вхождение числа в указанный диапазон от 120 до 240

$validator->inRange(223, 120, 240); //return true or false

// Проверка на корректный домен

$validator->isDomain('www.yandex.ru'); //return true or false
