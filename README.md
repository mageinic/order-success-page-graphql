# Order Success Page GraphQL

**Order Success Page GraphQL is a part of MageINIC Order Success Page extension that adds GraphQL features.** This extension extends Order Success Page definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/order-success-page-graph-ql

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Order Success Page requires installing [MageINIC Order Success Page](https://github.com/mageinic/Order-Success-Page) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/ordersuccesspage
```

## 2. How to use

- To view the queries that the **MageINIC Order Success Page GraphQL** extension supports, you can check `Order Success Page GraphQl User Guide.pdf` Or run `OrderSuccessPage Graphql.postman_collection.json` in Postman.

## 3. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
