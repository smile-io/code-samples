# BigCommerce PointsProducts Dropdown

This file will explain how to get setup.

## Implementation

1. Ensure you have Smile.io setup on your store
1. Copy the code in the `smile-points-products-dropdown.html` file in this repo
1. Add the code snippet below to your checkout
1. Add your public API key to the snippet
1. Implement adding the discount code to your cart in the `applyPointsPurchaseToCart` callback
1. You're all set!

## Snippets

### Points dropdown container

Add the following code to your checkout in the location you want to show the points dropdown.
```html
<div class="smile-points-products-dropdown"></div>
```
