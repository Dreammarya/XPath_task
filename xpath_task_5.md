## Go to the Shop page, write the XPath for quantity input of Oranges, Add to cart button for Oranges, and add to wish list for Oranges


### XPath Selectors for Quantity Input (Oranges)

```xpath
//input[@type="number" and @class="quantity"]
//input[@name="quantity_66b3a57b3fd5048eacb4798f"]
//div[contains(., "Orange")]//input[@class="quantity"]



### Add to Cart
```xpath
//div[contains(., "Orange")]//button[contains(text(), "Add to Cart")]


### Add to Wish List Button for Oranges
```xpath
//div[contains(., "Orange")]//button[./*[name()="svg"]]
