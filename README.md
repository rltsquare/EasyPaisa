# EasyPaisa-Magento2

# Overview

EasyPaisa payment is a Magento 2 extension that allows merchants to integrate with Easypay Online Payment System. Easypay Online Payment System is an e-payment solution that enables internet users to make transactions online. This extension can be easily integrated into any store. 
There are two payment options in the extension. First one is, Over the Counter and second one is, Mobile account. In the first payment option, whenever a customer orders on the store. A token number is generated and sent to the mobile phone. Customer can use this token number to pay at over 75,000 EasyPaisa shops across Pakistan. In the second method, customer can use the token number to pay directly through their EasyPaisa account. The plugin contains the enablement of following two facilities that are provided by Easypay Online Payment System:
    1. Redirection Based Easypay Integration
    2. Support for IPN feature
With this payment extension, your store will have an access to more than 10 million customers with EasyPaisa Mobile Account. The fact that customers can pay with one of the most widely used payment method in Pakistan will result in more purchases.

Here are some of the salient features for the extension:

```
1. Seamless integration of your online store with EasyPaisa API
2. Two different payment options for ease of the customers
3. Increase your customer base by bringing in clients from EasyPaisa platform
4. Compatible along with all other shipping methods
5. Data is highly secured and protected through built-in encryption
```

## Installation

### Magento® Marketplace

This extension will also be available on the Magento® Marketplace when approved.

### Manually

1. Go to Magento® 2 root folder

2. Require/Download this extension:

   Enter following commands to install extension.

   ```
   composer require rltsquare/easypaisa
   ```

   Wait while composer is updated.
   
   #### OR
   
   You can also download code from this repo under Magento® 2 following directory:
    
    ```
    app/code/RLTSquare/EasyPaisa
    ```

3. Enter following commands to enable the module:

   ```
   php bin/magento module:enable RLTSquare_EasyPaisa
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. If Magento® is running in production mode, deploy static content: 

   ```
   php bin/magento setup:static-content:deploy
   ```


## Requirements

1. This Magento® extension works on Magento 2.2 and 2.3 versions. Tested on versions 2.2.6 and above.

2. Tested on different themes specifically Ultimo, Porto and certain custom themes

For details, read our blog:
https://www.rltsquare.com/blog/easypaisa-magento-2-extension/
