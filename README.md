commerce_mov
============

Drupal Commerce Minimum Order Value

ABOUT

This Drupal 7 module for Commerce checks for minimum order value in cart page.

DEPENDENCIES
Drupal Commerce (https://www.drupal.org/project/commerce)

INSTALLING

- Extract the module into your sites/all/modules directory so it looks like sites/all/modules/commerce_mov
- Open commerce_mov.module file and change the values under function commerce_mov_order_settings()
	- By default, minimum order values for currencies INR & USD is set. You can remove either of them and replace with your own. Minimum of one value is required.
	- Also, set the value of continue_shopping_url to your store page.
- Navigate to Administration -> Modules and enable the module.

USAGE

- Browse to your store page and add items to the cart
- Go to the cart page to see if the minimum order value is being checked

CREDITS

Sridhar - sridhar@signature.co.in
