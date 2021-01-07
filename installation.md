# Installation

Installing [Livewire Crud](https://github.com/flightsadmin/livewire-crud) is really simple.

- You can install the package via [Composer](https://getcomposer.org/) `composer require flightsadmin/livewire-crud`

- Or add `"flightsadmin/livewire-crud" : "^2"` to your composer.json file and run `composer update` from your command line *you must be in the root of your project*

After running `composer require flightsadmin/livewire-crud` command just run

`php artisan crud:install`

**This command will perfom below actions:**

```
Compile css/js based on 'bootstrap and fontawesome/free'.
Run 'npm install && run dev'`
Flush 'node_modules' files from you folder.
```

If you choose to scaffold authentication this command will run `php artisan ui:auth` to generate Auth scaffolds using [`laravel/ui`](https://github.com/laravel/ui) package. You can skip this step if your app has authentication already. 
> **If you do not have Auth you will get missing variable error once you run your scaffolds, Therefore please unsure you have auth system installed or choose yes when prompted to install authentication**