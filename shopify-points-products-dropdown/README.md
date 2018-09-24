# Shopify PointsProducts Dropdown

This file will explain how to get setup.

## Implementation

1. Create a new **Snippet** in Shopify called `smile-points-products-dropdown.liquid`
2. Paste the code from this sample file in your new snippet
3. Hide rewards you don't want to offer at checkout using `hidePointsProductIds`
4. Include the following snippet before the closing `</body>` tag of your `checkout.liquid`
5. You're all set!

## Snippets

### Code to add to your checkout.liquid

```liquid
{% include 'smile-initializer' %}
{% include 'smile-points-products-dropdown' %}
```
