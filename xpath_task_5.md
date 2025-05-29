# 🍊 XPath Selectors for Oranges Product

This document contains XPath selectors for interacting with the Oranges product on the Shop page.

## 📋 Table of Contents
- [Quantity Input Selectors](#quantity-input-selectors)
- [Add to Cart Button Selectors](#add-to-cart-button-selectors)
- [Add to Wish List Button Selectors](#add-to-wish-list-button-selectors)

---

## 🔢 Quantity Input Selectors

### Generic Quantity Input
```xpath
//input[@type="number" and @class="quantity"]
```

### Specific Quantity Input by Name Attribute
```xpath
//input[@name="quantity_66b3a57b3fd5048eacb4798f"]
```

### Quantity Input within Orange Product Container
```xpath
//div[contains(., "Orange")]//input[@class="quantity"]
```

---

## 🛒 Add to Cart Button Selectors

### Add to Cart Button for Oranges
```xpath
//div[contains(., "Orange")]//button[contains(text(), "Add to Cart")]
```
---

## Add to Wish List Button Selectors

### Add to Wish List Button for Oranges
```xpath
//div[contains(., "Orange")]//button[./*[name()="svg"]]
```
---

