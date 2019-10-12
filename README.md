![Hungersoft.com](https://www.hungersoft.com/skin/front/custom/images/logo.png)

#  Multiple Flat Rate [M2]
**hs/module-multiple-flat-rate**

Hungersoft's [Multiple Flat Rate](https://www.hungersoft.com/p/magento2-multiple-flat-rate) extension allows you to add unlimited flat rate shipping methods to your store. You can easily configure the number of flat rate methods you need and, the name and code of each of these custom flat rate methods.

## Installation

```sh
composer config repositories.hs-module-all vcs https://github.com/hungersoft/module-all.git
composer config repositories.hs-module-multiple-flat-rate vcs https://github.com/hungersoft/magento2-multiple-flat-rate.git
composer require hs/module-multiple-flat-rate:dev-master

php bin/magento module:enable HS_All HS_MultipleFlatRate
php bin/magento setup:upgrade
```

## Support

Feel free to contact Hungersoft at support@hungersoft.com if you are facing any issues with this extension. Reviews, suggestions and feedback will be greatly appreciated.
