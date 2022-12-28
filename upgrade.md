# Upgrade

We push updates to this package frequently. Breaking Changes will be published in major updates.

Our package versioning follows [Semver](https://semver.org/) versioning

## How to upgrade from <small>v</small>1 to <small>v</small>2

During installation our package publishes stubs to `resources_path/views/vendor/livewire-crud`

!> v1 is for Laravel versions less than 9.19 which uses Webpack to compile Assests.

!> v2 is for Laravel versions greater than 9.19 which uses Vitejs to compile Assests.

To upgrade follow below steps

- [x]  Add `"flightsadmin/livewire-crud" : "^2"` to your composer.json file
- [x]  Run `composer update` from your command line *you must be in the root of your project*
- [x]  Run `php artisan vendor:publish`

**You can now customise your stubs in `resources_path/views/vendor/livewire-crud`**
> This upgrade does not update [`livewire/livewire`](https://github.com/livewire/livewire). You must follow upgrade guide from their repository if you are also upgrading this package. **However, use of our package does not necessarily mean you have to upgrade this**