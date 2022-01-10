## Magento 2 Arabic Language Pack

*Arabic Language* is your native language and you need to use that language on your magento 2 store. Please follow this article to get the **Magento 2 Arabic Language Pack** from Magento 2 translation project and install it more easily

## Overview

1. Language Package Process
2. Install Arabic Language Pack
3. How to active Arabic language pack
4. How to contribute
5. Supported Magento versions
6. Notes
7. Language package authors

## 1. How to Install Arabic Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Arabic language pack via composer is never easier.

**Install Arabic pack**:

With Marketing Automation (recommend):

```
composer require landofcoder/magento-2-arabic-language-pack:dev-master
php bin/magento setup:static-content:deploy ar_SA
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

**Update  Arabic pack**:

```
composer update landofcoder/magento-2-arabic-language-pack:dev-master
php bin/magento setup:static-content:deploy ar_SA
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```


### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Arabic language pack
- Step 2: Unzip Arabic pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Arabic language pack

You can download the language pack from above link

#### Step 2: Unzip Arabic pack

Unzip the Arabic language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip master.zip app/i18n/Landofcoder/
```

Rename folder `magento-2-arabic-language-pack` to `ar_sa`.


You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

### ✓ Method #3. Download and install manually (Not recommended)

To download and install Arabic pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `master.zip` into `app/i18n/Landofcoder/ar_sa/`

This language pack code is: **ar_sa**

#### Step 2: Flush cache

## 3. How to Active the Arabic language pack 

Now time to active the Arabic language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`


## 5. Supported Magento versions

It supports all Magento 2 versions include Magento 2 open-source (Community), Magento 2 Commerce (EE), Magento Cloud, Magento B2B, Magento MSI.


- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x
- Magento v2.3.x
- Magento v2.4.x

