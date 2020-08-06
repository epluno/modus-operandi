---
layout: page
title: WP Plugins
permalink: /system-administration/wp-plugins/
parent: System Administration
---

# Word Press Plugins

We use the following plugins in our current Wordpress multisite system.

## WooCommerce

[WooCommerce](https://wordpress.org/plugins/woocommerce/) is a flexible, open-source eCommerce solution. Basic features include:

- Product, Cart, and Checkout pages

- Secure payments by credit card and alternatives

- Configurable shipping options, including flat rates and [label printing](https://woocommerce.com/products/shipping/?utm_source=wp org repo listing&utm_content=3.6)

- Integrate content and commerce across your site via modular blocks

- [Automated tax calculations](https://woocommerce.com/products/tax/?utm_source=wp org repo listing&utm_content=3.6)

- [Google Analytics](https://woocommerce.com/products/woocommerce-google-analytics/?utm_source=wp org repo listing&utm_content=3.6), [MailChimp](https://woocommerce.com/products/mailchimp-for-woocommerce/?utm_source=wp org repo listing&utm_content=3.6), and [Facebook](https://woocommerce.com/products/facebook/?utm_source=wp org repo listing&utm_content=3.6) integration

- [Central store dashboard](https://woocommerce.com/posts/woocommerce-admin-a-new-central-dashboard-for-woocommerce/?utm_source=wp org repo listing&utm_content=3.6) with key metrics, and more.

### Stripe Payment Gateway

The [Stripe Payment Gateway](https://wordpress.org/plugins/woocommerce-gateway-stripe/) plugin extends WooCommerce allowing you to take payments directly on your store via Stripe’s API.

Accepts Visa, MasterCard, American Express, Discover, JCB, Diners Club, SEPA, Sofort, iDeal, Giropay, Alipay, and more directly on your store with the Stripe payment gateway for WooCommerce, including Apple Pay, Google Pay, and Microsoft Pay for mobile and desktop.

### Variation Swatches and Photos

[Variation Swatches and Photos](https://woocommerce.com/products/variation-swatches-and-photos/) replaces dropdown fields on your variable products with WooCommerce Color and Image Swatches.

Using color and image swatches provides a much nicer way to display variations of a product, available styles, available sizes, or pretty much anything else you can display using an image or color.

![img](https://t2232791.p.clickup-attachments.com/t2232791/39e32284-f477-49f3-a03f-6693365251c6/image.png)

## NS Cloner Pro

[NS Cloner Pro](https://neversettle.it/buy/wordpress-plugins/ns-cloner-pro/) is by far the easiest, fastest, and most user-friendly way you will ever create fully configured sites on your multisite networks. The NS Cloner will take any existing site on your WordPress multisite network and clone it into a new site that is completely identical in theme & theme settings, plugins & plugin configurations, content, pictures, videos, and site settings.

**Automation**

By using [WP CLI with NS Cloner](https://neversettle.it/documentation/ns-cloner/wp-cli-command-line-cloning/) we are able to automate the site cloning process. 

```
wp ns-cloner clone_basic 
  [--source=<id>]
    Source id of site to clone. Required.


  [--title=<title>]
    Title of target site. Required.


  [--name=<name>]
    Subdomain or subdirectory of target site. Required
```

## WP REST Cache

[WP REST Cache](https://wordpress.org/plugins/wp-rest-cache/) plugin will allow WordPress to cache the responses of the REST API, making it much faster.

## WordPress Multisite User Sync/Unsync

[WordPress Multisite User Sync/Unsync](https://wordpress.org/plugins/wp-multisite-user-sync/) plugin can sync/unsync users from one site (blog) to the other sites (blogs) in your WordPress Multisite Network.

## Really Simple SSL

[Really Simple SSL](https://wordpress.org/plugins/really-simple-ssl/) automatically detects your settings and configures your website to run over https.

To keep it lightweight, the options are kept to a minimum. The entire site will move to SSL.