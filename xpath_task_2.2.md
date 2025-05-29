Write the XPath of all input fields, sign in button, Create a new account link, and Go to Home link
1.input fields:
email address:
//*[@id="root"]/div/div/div[1]/div[1]/div/form/input[1]

//input[@type="email"]
//input[@placeholder="Email address"]
//form[@class="form"]//input[@type="email"]
/input[@class="form-input" and @type="email"]
Password:

//input[@type="password"]
//input[@placeholder="Password"]
//form[@class="form"]//input[@type="password"]
//input[@class="form-input" and @type="password"]


2.sign in button

//button[@type="submit"]
//button[@class="submit-btn"]
//button[text()="Sign In"]
//form[@class="form"]//button[@type="submit"]

/html/body/div[1]/div/div/div[1]/div[1]/div/form/button
3.Create a new account link

//a[@class="switch-link"]
//a[text()="Create a new account"]
//form[@class="form"]//a[@class="switch-link"]

4.Go to Home link

//a[@class="home-link"]
//a[text()="Go to Home"]
//form[@class="form"]//a[@class="home-link"]