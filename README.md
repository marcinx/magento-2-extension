# COINQVEST Extension for Magento 2

This is the official Magento module for COINQVEST. Accept and settle payments in digital currencies in your Magento shop.

This module for Magentor implements the PHP REST API documented at https://www.coinqvest.com/en/api-docs

## Key Features

* Accepts Bitcoin (BTC), Ethereum (ETH), Ripple (XRP), Stellar Lumens (XLM) and Litecoin (LTC) payments from customers.
* Instantly settles in your preferred national currency (USD, EUR, NGN, BRL).
* Integrates seemlessly into WooCommerce
* Sets the product price in your national currency.
* Automatically generates invoices.
* Eliminates chargebacks and gives you control over refunds.
* Eliminates currency volatility risks due to instant conversions and settlement.
* Translates the plugin into any required language.
* Includes payment state management for underpaid and completed payments.

## Requirements

* A COINQVEST merchant account -> Sign up [here](https://www.coinqvest.com).
* API Key and API Secret -> Find them [here](https://www.coinqvest.com/en/api-settings).
* Complete your account master data [here](https://www.coinqvest.com/en/account-settings).
* Download the extension from the Magento Marketplace [here](https://marketplace.magento.com/coinqvest-paymentgateway.html).


## Extension installation

* Create a folder structure in Magento root as app/code/Coinqvest/PaymentGateway.
* Download and extract the zip folder from the Magento Marketplace and upload the extension files to app/code/Coinqvest/PaymentGateway.
* Login to your SSH and run below commands:

    ```bash
    php bin/magento setup:upgrade
  
    // For Magento version 2.0.x to 2.1.x
    php bin/magento setup:static-content:deploy
  
    // For Magento version 2.2.x & above
    php bin/magento setup:static-content:deploy –f
   
    php bin/magento cache:flush
  
    ```
   
# Module Configuration

A detail configuration guide is available [here](https://www.coinqvest.com/en/blog/how-to-accept-bitcoin-and-get-paid-to-your-bank-account-with-coinqvest-for-magento-efbddb5e2829).

Please also inspect our [API documentation](https://www.coinqvest.com/en/api-docs) for more info or send us an email to service@coinqvest.com.

Support and Feedback
--------------------
Your feedback is appreciated! If you have specific problems or bugs with this Magento module, please file an issue on Github. For general feedback and support requests, send an email to service@coinqvest.com.

## Contributing
1. Fork it ( https://github.com/COINQVEST/magento-2-module/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request