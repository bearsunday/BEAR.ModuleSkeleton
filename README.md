# {vendor}/{module}

Skeleton Module for BEAR.Sunday


## Installation

### composer install

    composer require {vendor}/{module}:~0.1@dev
 
### Module install

```php
use path/to/SkeletonModule;

class AppModule extends AbstractModule
{
    /**
     * {@inheritdoc}
     */
    protected function configure()
    {
        $this->install(new {SkeletonModule});
    }
}

```

### Env

 * no
 
### Demo

 * n/a
 
