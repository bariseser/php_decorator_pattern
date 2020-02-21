# php_decorator_pattern
Decorator is a structural design pattern that lets you attach new behaviors to objects by placing these objects inside special wrapper objects that contain the behaviors.

```php
use IceCream\IceCream;
use IceCream\Nutty;

$iceCream = new IceCream();
$nutty = new Nutty($iceCream);
echo $nutty->makeIceCream() . PHP_EOL;
echo $nutty->getPrice() . PHP_EOL;
```
