### installation

```sh
composer install
composer require lookyman/composer-plugin-test-package:dev-master
```

### explanation

- processes phpstan configuration files in order:
    - extra.phpstan.configuration in composer.json
    - phpstan.neon
    - phpstan.neon.dist
- if file doesn't exist, asks to create it
- adds includes from package to file
- if package contains optional includes, asks to add them as well

### links

[https://github.com/lookyman/composer-plugin-test](https://github.com/lookyman/composer-plugin-test)

[https://github.com/lookyman/composer-plugin-test-package](https://github.com/lookyman/composer-plugin-test-package)
