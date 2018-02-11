=== Bitcoin Payments for WooCommerce ===
Contributors: gesman, bitcoinway.com
Tags: bitcoin, bitcoin wordpress plugin, bitcoin plugin, bitcoin payments, accept bitcoin, bitcoins
Requires at least: 3.0.1
Tested up to: 3.9
Stable tag: trunk
License: GPLv2 or later


Bitcoin Payments for WooCommerce is a Wordpress plugin that allows to accept bitcoins at WooCommerce-powered online stores.

== Description ==

Your online store must use WooCommerce platform (free wordpress plugin).
Once you installed and activated WooCommerce, you may install and activate Bitcoin Payments for WooCommerce.

= Benefits =

* Accept payment directly into your personal Electrum wallet.
* Electrum wallet payment option completely removes dependency on any third party service and middlemen.
* Accept payment in bitcoins for physical and digital downloadable products.
* Add bitcoin payments option to your existing online store with alternative main currency.
* Flexible exchange rate calculations fully managed via administrative settings.
* Zero fees and no commissions for bitcoin payments processing from any third party.
* Support 16 different currencies.
* Set main currency of your store in any of 16 currencies or bitcoin.
* Automatic conversion to bitcoin via realtime exchange rate feed and calculations.
* Ability to set exchange rate calculation multiplier to compensate for any possible losses due to bank conversions and funds transfer fees.


== Installation ==

1. Install "Bitcoin Payments for WooCommerce" wordpress plugin just like any other Wordpress plugin.
2. Activate.


== Screenshots ==

1. Checkout with option for bitcoin payment.
2. Order received screen, including QR code of bitcoin address and payment amount.
3. Bitcoin Gateway settings screen.


== Remove plugin ==

1. Deactivate plugin through the 'Plugins' menu in WordPress
2. Delete plugin through the 'Plugins' menu in WordPress


== Supporters ==

* Yifu Guo: http://bitsyn.com/
* Bitcoin Grants: http://bitcoingrant.org/


== Changelog ==

= 3.02 =
* Upgraded to support WooCommerce 2.1+
* Upgraded to support Wordpress 3.9
* Fixed bug in cron forcing excessive generation of new bitcoin addresses.
* Fixed bug disallowing finding of new bitcoin addresses to use for orders.
* Fixed buggy SQL query causing issues with delayed order processing even when desired number of confirmations achieved.
* Added support for many more currencies.
* Corrected bitcoin exchange rate calculation using: bitcoinaverage.com, bitcoincharts.com and bitpay.com
* MtGox APIs, services and references completely eliminated from consideration.

= 2.12 =
* Added 'bitcoins_refunded' field to order to input refunded value for tracking.

= 2.11 =
* Minor upgrade - screenshots fix.

= 2.10 =
* Added support for much faster GMP math library to generate bitcoin addresses. This improves performance of checkout 3x - 4x times.
  Special thanks to Chris Savery: https://github.com/bkkcoins/misc
* Improved compatibility with older versions of PHP now allowing to use plugin in wider range of hosting services.

= 2.04 =
* Improved upgradeability from older versions.

= 2.02 =
* Added full support for Electrum Wallet's Master Public Key - the math algorithms allowing for the most reliable, anonymous and secure way to accept online payments in bitcoins.
* Improved overall speed and responsiveness due to multilevel caching logic.

= 1.28 =
* Added QR code image to Bitcoin checkout screen and email.


= 1.27 =
* Fixed: very slow loading due to MtGox exchange rate API issues.

= 1.26 =
* Fixed PHP warnings for repeated 'define's within bwwc-include-all.php

= 1.25 =
* Implemented security check (secret_key validation logic) to prevent spoofed IPN requests.

= 1.24 =
* Fixed IPN callback notification invocation specific to WC 2.x

= 1.23 =
* Fixed incoming IP check logic for IPN (payment notification) requests.

= 1.22 =
* Fixed inability to save settings bug.
* Added compatibility with both WooCommmerce 1.x and 2.x

== Upgrade Notice ==

soon

== Frequently Asked Questions ==

soon
