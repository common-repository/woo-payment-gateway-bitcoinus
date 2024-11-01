=== WooCommerce Payment Gateway - Bitcoinus ===
Contributors: bitcoinus
Tags: woocommerce, woocommerce crypto-currency payment, bitcoinus payment gateway, woocommerce crypto-currency payment, payment processing, woocommerce bitcoin
Requires at least: 4.0
Tested up to: 5.3.1
Requires PHP: 5.2.4
Stable tag: trunk
License: GPL version 3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

WooCommerce Bitcoinus Payment Gateway plugin witch enables accepting payments for your online store via Bitcoinus.

== Description ==

[Bitcoinus](https://www.bitcoinus.com/) is a payment gateway which offers the most secure, efficient and fastest way to accept crypto payments for e-commerce business. At the moment, it supports top major cryptocurrencies including Bitcoin, Ethereum, Litecoin and more.

New Bitcoinus plugin added to the system will enable Wordpress merchants to accept cryptocurrency payments instantly and get paid in Euro directly to your bank account overcoming all crypto volatility. This means that every payment is fixed at a time transaction is initiated and not a penny will be lost even if cryptocurrencies decide to do some hula-hoops straight after the purchase is done. That is one of the key points why e-commerce businesses choose Bitcoinus. Also, there is no blockchain waiting time, most payments get accepted in only a couple of seconds and then (if necessary) automatically converted to EUR on merchant's Bitcoinus account.

Furthermore, easy integration and configuration guaranteed as this plugin module is fully set which means that no programming work is required, only copy/paste a few lines of credentials to insert crypto payments solution to the website.


= Account & Pricing =

To use the extension - you need to create the Bitcoinus merchant account [here](https://pay.bitcoinus.io/register). Bitcoinus transactions fee is only 0.5%.

= Features =

* __Free and easy integration;__
* __Extremely low transaction processing fee - almost free;__
* __Accepts and stores multiple cryptocurrencies;__
* __Converts received cryptocurrency to Euro and sends directly to any SEPA bank account (if preferred);__
* __Secure and fast transactions globally.__

= Demo =

[https://youtu.be/DW4PpyF1qzo](https://youtu.be/DW4PpyF1qzo)

= Security =

Customers are being redirected to Bitcoinus dedicated payment page in order to proceed with payment there. In the payment page customers are allowed to select any available crypto currency to pay with, no any other data about customers is required by Bitcoinus. It is up to merchant whether to send customers billing/contact information or information about items being purchased. Once merchant decides to send the information, billing/contact information is saved at Bitcoinus and available for the merchant. Information about purchased items is never stored by Bitcoinus, it is only used for showing customers their goods/services being purchased during payment. When the payment is processed, customers are redirected back to Wordpress page where payment status is showed. Bitcoinus module doesn't store any customer data in Wordpress database.

== Installation ==

1. Upload the woo-payment-gateway-bitcoinus folder to the to the /wp-content/plugins/plugin-name directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Select "WooCommerce" > "Settings" > "Payments" >"Bitcoinus" to configure the plugin
4. Bitcoinus Settings page, fill in the required fields. Project ID and secret key are available from your Bitcoinus account (Project Settings)
5. Click "Save Changes"

= Set callback URL =
1. Copy this URL to your Bitcoinus account's project settings section "Callback URL",
https://example.com/?wc-api=wc_gateway_bitcoinus
2. Change "example.com" to your e-commerce URL
3. Click "Save Changes".


== Screenshots ==

1. Bitcoinus settings.
2. Bitcoinus checkout page 1.
3. Bitcoinus checkout page 2.
