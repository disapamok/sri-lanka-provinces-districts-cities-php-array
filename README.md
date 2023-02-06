# Sri Lanka's provinces, districts, and cities in PHP array.
This has included Sri Lanka's all the provinces, districts, and cities in a PHP array.
Developers can use this class when they do want to let their visitors select their exact city.

## Installation

Via composer.

```bash
composer require disapamok/srilanka-cities
```

## Usage

```php

use Disapamok\Modules\SriLanka;


public function exampleFunction(){
    return SriLanka::getProvinces(); // Returns all provinces
    return SriLanka::getDiscricts('Province'); // Returns disdricts of a province
    return SriLanka::getCities('District'); // Returns cities of a district
}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

Author URL: [disapamok.com](http://disapamok.com)

## License
[MIT](https://choosealicense.com/licenses/mit/)
