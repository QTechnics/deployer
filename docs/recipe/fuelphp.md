<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit recipe/fuelphp.php -->
<!-- Then run bin/docgen -->

# fuelphp

[Source](/recipe/fuelphp.php)



* Require
  * [`recipe/common.php`](/docs/recipe/common.md)
* Config
  * [`shared_dirs`](#shared_dirs)
* Tasks
  * [`deploy`](#deploy)

## Config
### shared_dirs
[Source](/recipe/fuelphp.php#L9)

* Overrides [`shared_dirs`](/docs/recipe/common.md#shared_dirs) from `recipe/common.php`

FuelPHP 1.x shared dirs


## Tasks
### deploy
[Source](/recipe/fuelphp.php#L16)

Main task

This task is group task which contains next tasks:
* [`deploy:prepare`](/docs/recipe/common.md#deployprepare)
* [`deploy:vendors`](/docs/recipe/deploy/vendors.md#deployvendors)
* [`deploy:publish`](/docs/recipe/common.md#deploypublish)


