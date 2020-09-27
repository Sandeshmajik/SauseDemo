# TYL Test - Sauce Demo Cucumber test

The test is designed to run below scenario on Sauce:
1. Login to https://www.saucedemo.com/ using the "standard_user" account
2. Sort the products by Price (high to low)
3. Add the cheapest & the 2nd costliest products to your basket
4. Open the basket
5. Checkout
6. Enter details and Finish the purchase

Framework used:
The framework used includes Cucumber test scenario with Selenium WebDriver.

#### To triger build use command 

```mvn test```