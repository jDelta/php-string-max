# php-string-max

Singleton class for string formating.

Example:

```php
require __DIR__ . '/../vendor/autoload.php';

use jDelta\StringMax;

echo StringMax::format(
    'Hi {{name}}, keep {{tip}}!',
    [
        'name' => 'developer',
        'tip' => 'building'
   ]
);
// prints: Hi developer, keep building!

```
