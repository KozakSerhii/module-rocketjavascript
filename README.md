# [Magefan](https://magefan.com/) [Rocket JavaScript Extension for Magento 2](https://magefan.com/rocket-javascript-deferred-javascript)

[![Total Downloads](https://poser.pugx.org/magefan/module-rocketjavascript/downloads)](https://packagist.org/packages/magefan/module-rocketjavascript)
[![Latest Stable Version](https://poser.pugx.org/magefan/module-rocketjavascript/v/stable)](https://packagist.org/packages/magefan/module-rocketjavascript)

## Magento2 Footer JavaScript
## Magento2 Deferred JavaScript
## Magento2 Optimized Bundle JavaScript
  
## Configuration
  * To enable or disable extension please navigate to Magento 2 Admin Panel > Stores > Magefan Extensions > Rocket JavaScript

## Requirements
  * Magento Community Edition 2.1.x-2.2.x or Magento Enterprise Edition 2.1.x-2.2.x
  
## Installation
* [Install Rocket JavaScript Extension for Magento 2 via Composer or anarchive](https://magefan.com/blog/rocket-javascript-installation)

## Get List Of Used JS On A Sigle Page
```
/* Use in browser console */
/* Replace PATH_TO_JS with a string of static content URL including language. E.g.
'https://domain.com/pub/static/version1549034518/frontend/Magento/luma/en_US/'
*/
globalSrc = '';
jQuery('script').each(function(){
if (!jQuery(this).attr('src')) return;
var src = jQuery(this).attr('src');
if (src.indexOf('https://' + window.location.hostname) != -1 || src.indexOf('http://' + window.location.hostname) != -1) {
var src = (src.replace(PATH_TO_JS, ''));
globalSrc += "\n" + src;
}
})
console.log(globalSrc);

```

## Support
If you have any issues, please [contact us](mailto:support@magefan.com)
then if you still need help, open a bug report in GitHub's
[issue tracker](https://github.com/magefan/module-rocketjavascript/issues).

Please do not use Magento Marketplace's Reviews or (especially) the Q&A for support.
There isn't a way for us to reply to reviews and the Q&A moderation is very slow.

## License
The code is licensed under [Open Software License ("OSL") v. 3.0](http://opensource.org/licenses/osl-3.0.php).

## Other Magento 2 Extensions by Magefan
  * [Magento 2 Blog Extension](https://magefan.com/magento2-blog-extension)
  * [Magento 2 Blog Plus Extension](https://magefan.com/magento2-blog-extension/pricing)
  * [Magento 2 Blog Extra Extension](https://magefan.com/magento2-blog-extension/pricing)
  * [Magento 2 Login As Customer Extension](https://magefan.com/login-as-customer-magento-2-extension)
  * [Magento 2 Convert Guest to Customer Extension](https://magefan.com/magento2-convert-guest-to-customer)
  * [Magento 2 Facebook Open Graph Extension](https://magefan.com/magento-2-open-graph-extension-og-tags)
  * [Magento 2 Auto Currency Switcher Extension](https://magefan.com/magento-2-currency-switcher-auto-currency-by-country)
  * [Magento 2 Auto Language Switcher Extension](https://magefan.com/magento-2-auto-language-switcher)
  * [Magento 2 GeoIP Switcher Extension](https://magefan.com/magento-2-geoip-switcher-extension)
  * [Magento 2 YouTube Widget Extension](https://magefan.com/magento2-youtube-extension)
  * [Magento 2 Product Widget Advanced Extension](https://magefan.com/magento-2-product-widget)
  * [Magento 2 Conflict Detector Extension](https://magefan.com/magento2-conflict-detector)
  * [Magento 2 Lazy Load Extension](https://magefan.com/magento-2-image-lazy-load-extension)
  * [Magento 2 Rocket JavaScript Extension](https://magefan.com/rocket-javascript-deferred-javascript)
  * [Magento 2 CLI Extension](https://magefan.com/magento2-cli-extension)
