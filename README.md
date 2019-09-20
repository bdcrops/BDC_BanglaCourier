# BDC_BanglaCourier

This module is used as Offline Shipping methods of  Magento 2 extensions.



## 1. How to install & upgrade BDC_BanglaCourier


#### 1.1 Copy and paste

If you don't want to install via composer, you can use this way.

- Download [the latest version here](https://github.com/bdcrops/module-banglacourier/archive/master.zip)
- Extract `master.zip` file to `app/code/BDC/BanglaCourier` ; You should create a folder path `app/code/BDC/BanglaCourier` if not exist.
- Go to Magento root folder and run upgrade command line to install `BDC_BanglaCourier`:

#### 1.2. Install via composer

We recommend you to install BDC_BanglaCourier module via composer. It is easy to install, update and maintaince.Run the following command in Magento 2 root folder.
```
composer config repositories.module-banglacourier git
https://github.com/bdcrops/module-banglacourier.git

composer require bdcrops/module-banglacourier:~1.0.0
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
#### 1.3 Upgrade    

```
composer update bdcrops/module-banglacourier
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
Run compile if your store in Product mode:
```
php bin/magento setup:di:compile
```

## 2 Manual Tutorial

- Admin Panel Sales & Shipping section Show as below:
![](docs/BanglaCourierAdmin1.png)
![](docs/BanglaCourierAdmin2.png)

- The Order Summary section of the Review & Payments step should also reflect on the method
selected in the Shipping step, as follows:

![](docs/BanglaShippingChkout.png)
