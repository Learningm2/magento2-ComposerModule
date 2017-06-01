**Magento 2 module**

### Install via composer

Run the following command in Magento 2 root folder

```
php bin/magento module:status
php bin/magento module:enable Learning_ComposerModule
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```