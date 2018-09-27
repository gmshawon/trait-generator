# Laravel Trait Generator
Laravel Generator For Creating New Traits

## Installation

Install using composer
```
composer require cedextech/trait-generator
```

Add the service provider, open `config/app.php`, and add a new item to the providers array.

```
Cedextech\TraitGenerator\ServiceProvider::class,
```

That's it! You're all set to go. Run the `php artisan` command from the Terminal to see the new `make:trait` command.

## Usage

```
php artisan make:trait UserTrait
```

Note: Also remember to import the models which are being used in the trait.

Another discussion about trait:
https://stackoverflow.com/questions/40288657/how-to-make-a-trait-in-laravel

## Explanation

https://medium.com/cedex-technologies-llp/laravel-5-5-trait-generator-b83202a72294
