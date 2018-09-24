# Shopify Points Slider

This file will explain how to get setup.

## Implementation

1. Create a new **Snippet** in Shopify called `smile-points-slider.liquid`
2. Paste the code from this sample file in your new snippet
3. Set the PointsProduct ID at the top of the snippet you wish to use for the slider at checkout
4. Include the following snippet before the closing `</body>` tag of your `checkout.liquid`
5. You're all set!

## Snippets

### Code to add to your checkout.liquid

```liquid
{% include 'smile-initializer' %}
{% include 'smile-points-slider' %}
```
