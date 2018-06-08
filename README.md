# Magento 2.2.* Fix for Issue #11354
[![Latest Stable Version](https://poser.pugx.org/sashas/merged-css-issue/v/stable)](https://packagist.org/packages/sashas/merged-css-issue)
[![Total Downloads](https://poser.pugx.org/sashas/merged-css-issue/downloads)](https://packagist.org/packages/sashas/merged-css-issue)
[![Latest Unstable Version](https://poser.pugx.org/sashas/merged-css-issue/v/unstable)](https://packagist.org/packages/sashas/merged-css-issue)
[![License](https://poser.pugx.org/sashas/merged-css-issue/license)](https://packagist.org/packages/sashas/merged-css-issue)

This is a temporary fix for the Issue [Issue #11354](https://github.com/magento/magento2/issues/11354)

This module works only with Magento 2.2.4 version and need to be removed after upgrade/downgrade. Assumed that the issue will be fixed in the new release. 

## 1. How to install module

Run the following command in Magento 2 root folder:

```
composer require sashas/merged-css-issue
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```

## 2. How to uninstall module

Run the following command in Magento 2 root folder:

```
composer remove sashas/merged-css-issue
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```
