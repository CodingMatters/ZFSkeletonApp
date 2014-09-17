ZFSkeletonApp
=============
[![Latest Stable Version](https://poser.pugx.org/codingmatters/zf-skeleton-app/v/stable.svg)](https://packagist.org/packages/codingmatters/zf-skeleton-app) [![Total Downloads](https://poser.pugx.org/codingmatters/zf-skeleton-app/downloads.svg)](https://packagist.org/packages/codingmatters/zf-skeleton-app) [![Latest Unstable Version](https://poser.pugx.org/codingmatters/zf-skeleton-app/v/unstable.svg)](https://packagist.org/packages/codingmatters/zf-skeleton-app) [![License](https://poser.pugx.org/codingmatters/zf-skeleton-app/license.svg)](https://packagist.org/packages/codingmatters/zf-skeleton-app)

Initial Zend Framework skeleton application structure


Submodules
----------

#### [ZFModuleIni](https://github.com/CodingMatters/ZFModuleIni) ####
[![Latest Stable Version](https://poser.pugx.org/codingmatters/zf-module-ini/v/stable.svg)](https://packagist.org/packages/codingmatters/zf-module-ini) [![Total Downloads](https://poser.pugx.org/codingmatters/zf-module-ini/downloads.svg)](https://packagist.org/packages/codingmatters/zf-module-ini) [![Latest Unstable Version](https://poser.pugx.org/codingmatters/zf-module-ini/v/unstable.svg)](https://packagist.org/packages/codingmatters/zf-module-ini) [![License](https://poser.pugx.org/codingmatters/zf-module-ini/license.svg)](https://packagist.org/packages/codingmatters/zf-module-ini) 

A Generic "Application" module which includes initial configurations like application name, site URL and company/developer name. Learn more about its features [here](https://github.com/CodingMatters/ZFModuleIni).

Installation
------------

Using Composer (recommended)
----------------------------
The recommended way to get a working copy of this project is to clone the repository
and use `composer` to install dependencies using the `create-project` command:

    curl -s https://getcomposer.org/installer | php --
    php composer.phar create-project --prefer-source --no-dev codingmatters/zf-skeleton-app path/to/install

Alternately, clone the repository and manually invoke `composer` using the shipped
`composer.phar`:

    cd my/project/dir
    git clone git://github.com/CodingMatters/ZFSkeletonApp.git
    cd MegaOfficeTool
    git submodule init
    git submodue update
    php composer.phar self-update
    php composer.phar install

(The `self-update` directive is to ensure you have an up-to-date `composer.phar`
available.)