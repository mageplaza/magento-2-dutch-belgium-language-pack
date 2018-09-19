## Magento 2 Dutch, Belgium Language Pack



Read more [Magento 2 Dutch, Belgium Language Pack](https://www.mageplaza.com/magento-2-dutch-belgium-language-pack.html)


## Overview

- 1. Language Package Process
- 2. Install Dutch, Belgium Language Pack
- 3. How to active Dutch, Belgium language pack
- 4. How to contribute
- 5. Supported Magento versions

## 1. Language Package Process

This is status of Dutch, Belgium Language Pack, you can see how many percentage of this project has been done.

![language pack](http://progressed.io/bar/80?title=translated)

It is not fully translated? Feel free to contribute:
- [On Crowdin](https://crowdin.com/project/magento-2): It takes time to approve your contribution by Magento team.
- [On Github](https://github.com/mageplaza/magento-2-dutch-belgium-language-pack/blob/master/HOW-TO-CONTRIBUTE.md): It's faster, our team will approve it after you send pull request.


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Dutch, Belgium Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Dutch, Belgium language pack via composer is never easier.

**Install Dutch, Belgium pack**:

```
composer require mageplaza/magento-2-dutch-belgium-language-pack:dev-master
php bin/magento setup:static-content:deploy nl_BE
php bin/magento cache:flush

```


**Update  Dutch, Belgium pack**:

```
composer update mageplaza/magento-2-dutch-belgium-language-pack:dev-master
php bin/magento setup:static-content:deploy nl_BE
php bin/magento cache:flush

```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Dutch, Belgium language pack
- Step 2: Unzip Dutch, Belgium pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Dutch, Belgium language pack

You can download the language pack from above link

#### Step 2: Unzip Dutch, Belgium pack

Unzip the Dutch, Belgium language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip master.zip app/i18n/Mageplaza/nl_be
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Dutch, Belgium pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-dutch-belgium-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-dutch-belgium-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `nl_BE.zip` into `app/i18n/mageplaza/nl_BE/nl_BE.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to active Dutch, Belgium language pack

Now time to active the Dutch, Belgium language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Dutch, Belgium language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute

Contribute to this language at https://crowdin.com/project/magento-2/nl-BE

## 5. Supported Magento versions

It supports all Magento 2 versions include [Magento 2 open-source](https://www.mageplaza.com/download-magento/), Magento 2 Commerce.


- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x



## 6. Note

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/mageplaza/magento-2-dutch-belgium-language-pack/issues/new)

## 7. Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## 8. References:

- https://www.mageplaza.com/magento-2-dutch-belgium-language-pack.html
- https://crowdin.com/project/magento-2




## Mageplaza extensions on Magento Marketplace, Github


- [Layered Navigation](https://marketplace.magento.com/mageplaza-layered-navigation-m2.html)
- [One Step Checkout](https://marketplace.magento.com/mageplaza-magento-2-one-step-checkout-extension.html)
- [SMTP](https://marketplace.magento.com/mageplaza-module-smtp.html) ; [SMTP on Github](https://github.com/mageplaza/magento-2-smtp)
- [Blog](https://github.com/mageplaza/magento-2-blog)
- [Security](https://marketplace.magento.com/mageplaza-module-security.html)
- [Social Login](https://github.com/mageplaza/magento-2-social-login)
- [SEO](https://github.com/mageplaza/magento-2-seo) ; [SEO on Marketplace](https://marketplace.magento.com/mageplaza-magento-2-seo-extension.html)
- [SMTP](https://github.com/mageplaza/magento-2-smtp)
- [Product Slider](https://github.com/mageplaza/magento-2-product-slider)
- [Banner](https://github.com/mageplaza/magento-2-banner-slider)
- [Sample Payment Method](https://github.com/mageplaza/magento-2-sample-payment-method)



