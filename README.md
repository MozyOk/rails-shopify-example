# Shopify Rails

```
$ brew tap shopify/shopify
$ brew install shopify-cli
$ rbenv local 2.6.6
$ shopify create
$ bundle
$ rails g shopify_app:home_controller
$ rails g shopify_app:shop_model
$ rails db:migrate
$ shopify populate customers
$ shopify populate draftorders
$ shopify populate products
```
```
$ rbenv local 2.6.6
$ bundle
$ cp .env-example .env
Edit .env
$ rails db:migrate
```
