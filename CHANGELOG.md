## Version 1.1.5

* Adds support for Klarna XML-RPC API.
* Implements the 'Klarna Order Management' activate method.

## Version 1.1.4

* Allows specifying which Klarna order attributes to update. This can be used for only updating the order status or adding a merchant reference to an existent order.
* Allows updating an order after initializing it.
* Initial commit for 'Germany only' attributes support.
* Client update_order can also be used to create a new order if id is not present.

## Version 1.1.3

* Fix a bug where shipping address would not be passed to Klarna

## Version 1.1.2

* Fix a bug where GUI options were passed on persisted orders (not allowed)

## Version 1.1.1

* Fix a bug where GUI options would not be passed to Klarna

## Version 1.1.0

* Exceptions raised now include the response body

## Version 1.0.1

* Fix bug with assigning `[]` to `Cart#items`

## Version 1.0.0

* Inherit exceptions from StandardError
* Refactored `Client`-class
* Removed custom `deep_merge`-ext

## Version 0.0.6

* Client-side validations
* `Client#update_order`
* Global configuration and default values
* Fixes a bug with `Order#merchant_reference` format

## Version 0.0.5

* Exceptions when requests to server fail
* Cleanup in Gemspec
* CI

## Version 0.0.4

_Gone_

## Version 0.0.3

_Nothing_

## Version 0.0.2

* `Client#environment` attribute

## Version 0.0.1

* Bootstrapping
* `Client#create_order`
* `Client#read_order`
