## Stripe SOFORT

### Go to WooCommerce > Settings > Checkout > Stripe SOFORT

### Click on Enable and save

### Click Save changes button at the bottom

I see **Your settings have been saved** notice.

Be sure to also copy the webhook endpoint provided on the settings page and add it to your Stripe Dashboard API/Webhook setting.

### Go to WooCommerce > Settings > General

### Set currency to Euro

### Click Save changes button at the bottom

I see **Your settings have been saved** notice.

### Add a product to cart

### Go to the checkout page

I see Stripe SOFORT is available as a payment method.

### Fill in all required details

### Select Stripe SOFORT as payment method if not selected already

### Select a SOFORT ***Country origin of your bank.***

### Click on **Place order** button

I see a redirect Stripe page simulating an authorization. I also see two options **Fail Test Payment** and **Authenticate Test Payment**.

### Click on ***Authenticate Test Payment***

It redirects me to Order received page. I can see the order number and Stripe
as the payment method.

### Go to the admin dashboard and click WooCommerce

I see the order number I created from checkout.

### Click the order number

I see the order status is on-hold and from Order notes there's **Stripe awaiting payment**. I understand I may not see the order status changed to processing/completed right away as some payment methods are asynchronous and can take a little time to trigger. But eventually I see the change. Note for this payment method, order status will not change in test mode.
