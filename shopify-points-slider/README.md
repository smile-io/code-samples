# Shopify Points Slider

This file will explain how to get setup.

## Implementation

1. Create a new **Snippet** in Shopify called `sweettooth-points-slider.liquid`
2. Paste the code from this sample file in your new snippet
3. Set the points product id at the top of the snippet you wish to use for the slider at checkout
4. Include the following snippet before the closing `</body>` tag of your `checkout.liquid`
5. You're all set!

## Snippets

### Code to add to your checkout.liquid

```liquid
{% include 'sweettooth-initializer' %}
{% include 'sweettooth-points-slider' %}
```
