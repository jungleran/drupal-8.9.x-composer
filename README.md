```
bash build.sh
cd DRUPAL_8.9.x_ROOT
time docker run --rm -v ${PWD}:/app -v ${HOME}/.composer:/root/.composer -e COMPOSER_ROOT_VERSION=8.9.x-dev -w /app jungleran/composer:1.9.1 composer update -vvv 
```
