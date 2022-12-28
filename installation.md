# Installation

Installing [Livewire Crud](https://github.com/flightsadmin/livewire-crud) is really simple.

- You can install the package via [Composer](https://getcomposer.org/) 

> `composer require flightsadmin/livewire-crud`


After running `composer require flightsadmin/livewire-crud` command just run

`php artisan crud:install`

**This command will perfom below actions:**

```
Compile css/js based on 'bootstrap and fontawesome/free' using asset bundler relevant to you Laravel Version, Vitejs or Webpack.
Flush 'node_modules' files from you folder.
```

If you choose to scaffold authentication this command will run `php artisan ui:auth` to generate Auth scaffolds using [`laravel/ui`](https://github.com/laravel/ui) package. You can skip this step if your app has authentication already. 

> **If you do not have Auth you will get missing variable error once you run your scaffolds, Therefore please unsure you have auth system installed or choose yes when prompted to install authentication**