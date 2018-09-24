# Points Slider

This file will explain how to get setup.

## Implementation

1. Ensure you have Smile.io setup on your store
1. Copy the code in the `smile-points-slider.html` file in this repo
1. Add the code snippet below to your checkout
1. Add your public API key to the snippet
1. Implement adding the discount code to your cart in the `applyPointsPurchaseToCart` callback
1. You're all set!

## Snippets

### Points slider container

Add the following code to your checkout in the location you want to show the points slider:
```html
<div class="smile-points-slider" data-points-product-id=21></div>
```

Be sure to replace `21` with the ID of the points product that you want to use with the slider!
