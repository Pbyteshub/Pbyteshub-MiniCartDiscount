# Mage2 Module Pbyteshub MiniCartDiscount

    ``pbyteshub/module-minicartdiscount``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities
Display Discount Price To Mini Cart.

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Pbyteshub`
 - Enable the module by running `php bin/magento module:enable Pbyteshub_MiniCartDiscount`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require pbyteshub/module-minicartdiscount`
 - enable the module by running `php bin/magento module:enable Pbyteshub_MiniCartDiscount`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration




## Specifications

 - Plugin
	- afterCart - Magento\Checkout\CustomerData\Cart > Pbyteshub\MiniCartDiscount\Plugin\Magento\Checkout\CustomerData\Cart


## Attributes



