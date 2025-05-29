# XPath Practice Exercises - Solutions

## 1. Write the XPath to locate the main **h1** element.
```xpath
//header/h1
```

## 2. Write the XPath to select the **About Us** navigational link.
```xpath
//nav//a[text()="About Us"]
//a[@href="#about" and @class="nav-link"]
```

## 3. Write the XPath to select the **Graphic Design** dropdown link.
```xpath
//ul[@class="dropdown"]//a[@href="#graphicdesign"]
//ul[@class="dropdown"]//a[text()="Graphic Design"]
```

## 4. Write the XPath to select the team member's name **Jane Smith**.
```xpath
//div[@class="team"]//h4[text()="Jane Smith"]
//div[@class="team"]//li[2]/h4
```

## 5. Write the XPath to select the description (which is inside the paragraph) of **SEO Services**.
```xpath
//div[@class="service-item"][3]/p
//div[@class="service-item"][h3[text()="SEO Services"]]/p
```

## 6. Write an XPath expression to select all service items in the "**Our Services**" section.
```xpath
//section[@id="services"]//div[@class="service-item"]
```

## 7. What is the XPath to select the **email input field** in the contact form?
```xpath
//input[@id="email"]
```

## 8. How would you write an XPath to select the **entire contact form**?
```xpath
//section[@id="contact"]//form[@id="contactForm"]
```

## 9. Provide the XPath to select the **footer paragraph element**.
```xpath
//footer/p
```

## 10. What is the XPath to select the **first team member**'s (`<h4>`) name?
```xpath
//div[@class="team"]//li[1]/h4
```

## 11. How can you select the description of the **second service** item using XPath?
```xpath
//div[@class="service-list"]/div[@class="service-item"][2]/p
```

## 12. What is the XPath to select the "Contact Us" section header (`<h2>` element)?
```xpath
//h2[text()="Contact Us"]
```

## 13. Write an XPath expression to select all links within the dropdown under the "Services" navigation item.
```xpath
//ul[@class="dropdown"]/li/a
```

## 14. What is the XPath to select the first `<li>` under the "Our Team" section?
```xpath
//div[@class="team"]/ul/li[1]
```

## 15. Provide the XPath to locate the "Send Message" button in the contact form.
```xpath
//form[@id="contactForm"]//input[@value="Send Message"]
```
