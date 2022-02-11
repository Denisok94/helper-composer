Использование / Using: Helper Class
===================================

```php
use \denisok94\helper\Helper as H;
```
Можно создать в любом удобном месте своего приложения, например в папке `components`, файл `H.php` с классом `H` и унаследовать его от `Helper`.
Внутри класса `H` добавить свои функции с повторяющемся действиями или перезаписать имеющиеся в `Helper`.

You can create a file in any convenient place of your application, for example, in the `components` folder `H.php` with class `H` and inherit it from `Helper`.
Inside the `H` class, add your own functions with repetitive actions or overwrite the existing ones in the `Helper`.

```php
namespace app\components;
use \denisok94\helper\Helper;
class H extends Helper {}
```

И в дальнейшем использовать его. 
And use it in the future.

```php
use app\components
```